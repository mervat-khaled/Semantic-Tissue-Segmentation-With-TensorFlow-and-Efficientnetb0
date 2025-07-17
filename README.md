# Semantic-Tissue-Segmentation-With-TensorFlow-and-Efficientnetb0
This project was completed as part of the "Deep Learning" course at Nile University.

# About The Data:
Panoptic segmentation of nUclei and tissue in advanced MelanomA:
Melanoma is an aggressive form of skin cancer with increasing incidence. While primary melanoma is often treated with surgical excision, advanced melanoma requires immune checkpoint inhibition therapy. Unfortunately, half of the patients do not respond to this therapy, which is costly and potentially toxic. 
## For further information about the data check this [Link](https://puma.grand-challenge.org/)

# GOAL
In this project, we tend to solve the task 1 in track 1, wich is Semantic tissue segmentation, using a pretrained U-net from segmentation model's module with EfficientNetB0 as a backbone “Encoder”. The performance was evaluated by Dice Coefficient (DSC), Dice Loss, IOU (Intersection Over Union) score. 

## Image Enhancment:
To improve the contrast in images, which can make edges and boundaries more distinct, we applied 4 preprocessing techniques:  
* CLAHE (contrast limited adaptive histogram equalization)
* Contrast Starching
* Power Law transformation
* CIELAP method to convert a color image to gray scale

### For further details check the Documentation file [documentation.pdf](https://github.com/mervat-khaled/Semantic-Tissue-Segmentation-With-TensorFlow-and-Efficientnetb0/blob/main/documentation.pdf) 

 
