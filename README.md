
#  Semantic Segmentation Using Pixel Transposed CNN

The aim of this study is to solve the checkerboard problem, which is caused by the existence of no direct relationship among adjacent pixels on the output feature map. This can be solved by Pixel TCN.

## Dataset
To conduct the study, we utilized the PASCAL 2012 segmentation dataset for the specific purpose of evaluating the effectiveness of the proposed pixel transposed convolutional techniques in semantic image segmentation tasks.

The 2012 dataset consists of images from 2008-2011 for which additional segmentations had been prepared. As in previous years the task to training/check units has been maintained. The overall variety of images with segmentation has been extended from 7,062 to 9,993. 

Sample images from the dataset is provided below:
 - Original picture(left) 
 - Object detection(right)

![Screenshot](https://github.com/revyarly/Semantic-Segmentation-Using-Pixel-Transposed-CNN/blob/main/original%20picture.jpg)
![Screenshot](https://github.com/revyarly/Semantic-Segmentation-Using-Pixel-Transposed-CNN/blob/main/object%20detection.jpg)

## Tech Stack

**Programming Languages:** Python

**Methods Used:** Machine Learning, Deep Learning, Data pre-processing. 

## Architecture 

![a](https://github.com/revyarly/Semantic-Segmentation-Using-Pixel-Transposed-CNN/blob/main/architecture.png)

## Documentation

Here is the link to the [documentation](https://github.com/revyarly/Semantic-Segmentation-Using-Pixel-Transposed-CNN/blob/main/documentation.pdf)

## Usage

To reproduce the predictions, follow these steps:

1. Clone the repository
2. Install the required packages
3. Run the `.ipynb` files to preprocess the data and train the models and return the output

**Note:** refer to **architecture** to understand the structure of the model.   

## Conclusion

In this study, we propose the Pixel TCL, which overcomes the checkerboard problem raised in DCLs. The checkerboard problem occurs because there is no direct relationship between the intermediate feature maps generated in DCLs. The Pixel TCL introduces direct dependencies between the generated intermediate feature maps. It generates intermediate feature maps sequentially so that the later maps depend on the previously generated ones. The establishment of dependencies in Pixel TCL ensures that adjacent pixels on the output feature maps are directly related.

Experimental results on semantic segmentation and image generation tasks demonstrate that Pixel TCL effectively overcomes the checkerboard problem. Furthermore, the results of the semantic image segmentation task show that Pixel TCL can recall nearby spatial features such as edges and shapes, resulting in more precise segmented outcomes.

In the future, Pixel TCL can be made more efficient in a broader range of models, including other effective models such as Generative Adversarial Networks (GANs).
