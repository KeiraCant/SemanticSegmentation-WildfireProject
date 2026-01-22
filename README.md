

# Semantic Segmentation for Land Use Segmentation

A deep learning project for land use segmentation using convolutional neural networks with varying encoder depths.


## Models

This repository contains semantic segmentation models with different encoder architectures:

- **3-layer encoder**: Available in `3_layer`
- **4-layer encoder**: Model too large for GitHub (contact for access)
- **5-layer encoder**: Model too large for GitHub (contact for access)

### Obtaining Large Models

Due to file size limitations on GitHub, the 4-layer and 5-layer models are not included in this repository. To obtain these models, please contact myself.



## Results

Test outputs and evaluation metrics can be found in the `predictions` directory.

## Training and Testing Code

The code is also provided to train and test the U-NET model. 

## Dataset

The dataset is taken from landcover.ai. The link to their work can be found here. https://landcover.ai.linuxpolska.com/

@InProceedings{Boguszewski_2021_CVPR,
    author = {Boguszewski, Adrian and Batorski, Dominik and Ziemba-Jankowska, Natalia and Dziedzic, Tomasz and Zambrzycka, Anna},
    title = {LandCover.ai: Dataset for Automatic Mapping of Buildings, Woodlands, Water and Roads from Aerial Imagery},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month = {June},
    year = {2021},
    pages = {1102-1110}
}
