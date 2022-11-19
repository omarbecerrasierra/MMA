# Semantic Segmentation for Aerial Imagery Recognition: a Deep Learning Approach
> Image semantic segmentation is a technique of increasing interest among researchers. It is useful in a wide variety of fields: from facial recognition, autonomous vehicles, medical diagnosis to urban planning. On the other hand, the use of deep learning algorithms has brought big success on image processing problems. This project aims to address this problem with a deep learning approach by using a U-Net architecture. To test our approach we use a dataset of satellite images of Dubai and we train the model with different architectures for the encoding. We found that the encoders that best performed were resnet18, vgg13 and efficientnet-b3. Our results support that U-Net behaves very well for semantic segmentation problems.

## General Information

`Research question`

Is it possible to classify key areas of a city with high performance through a semantic segmentation map from aerial images?

`Objectives`

**General Objective:** To generate a semantic segmentation map of a city using aerial images in order to classify key areas.

**Specific Objectives:**
- To analyze the data and apply the required transformations.
- To implement several Deep Learning architectures that can identify the key areas in the city.
- To evaluate and compare the performance in the segmentation task of  the different architectures including precision and recall metrics. 
- To contrast the obtained results with previous ones addressed in the literature.


## Main Technologies Used
- Pytorch  - version 1.12.1
- Sklearn  - version 1.0.2

## Setup
1. Download the dataset from Kaggle in this [Link](https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery). This correspond to Humans in the Loop is publishing an open access dataset annotated for a joint project with the Mohammed Bin Rashid Space Center in Dubai, the UAE. 

2. Load the dataset on a Google Drive in this case use the route **MyDrive/dataset**

3. Install the libraries for run in Google Colab the code, the unique libraries thatis not include in  colab and require instalation segmentation_models_pytorch, install the libraries with this command:

    `!pip install segmentation_models_pytorch`
    
4. The notebbok is configurated for run with this specifycation 




## Project Status
Project is: _complete_

## Acknowledgements

- This project was inspired by the Competence creates in Kaggle, for this we use the MBRSC data set that which exists under the Creative Commons Zero (CC0) license and is available to download (Kaggle 2020). It contains aerial imagery of Dubai obtained by MBRSC satellites and annotated with pixel-wise semantic segmentation in 6 classes.

- This project was based on [this tutorial](https://www.coursera.org/lecture/convolutional-neural-networks/semantic-segmentation-with-u-net-rEYzz).

## Contact

Created by:
- Omar Alexis Becerra
- Catalina Lesmes Ramírez
- Luisa Fernanda Londoño
- Pedro Urrego Gómez

MSc. in Applied Mathematics, Universidad EAFIT, Medellín, Colombia

> Corresponding Email: purregog@eafit.edu.co - feel free to contact me!



## License
This project is open source and available under the MIT License.


