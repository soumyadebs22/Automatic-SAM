# Automatic Co-segmentation

Automatic Co-Segmentation of Images based on Segment Anything Model(SAM) The project focuses on the enhancement of the Segment Anything Model (SAM)and its personalised variant, PerSAM, for developing an automatic co-segmentation algorithm. In image co-segmentation, given a set of similar images, the common object needs to be segmented out from each image. We also sub-group the images using k-means and try to generate co-saliency maps by fusing aligned saliency maps. However, instead of aligning saliency maps, we use PerSAM to generate candidate masks by passing saliency masks as proxy for the required masks in PerSAM. More specifically, we use VST for saliency generation.

## Project Overview

In this project, we aim to automate the segmentation process by identifying common features across multiple images to segment the desired object. The entire work is conducted on Google Colab, making it accessible without specific system requirements.

### Models Used
- **Segment Anything Model (SAM)**: A versatile model for general segmentation tasks.
- **Personalised Segment Anything (Per-SAM)**: Customized segmentation tailored to specific needs.
- **Visual Saliency Transformer (VST)**: A model that focuses on identifying visually salient regions in images.

## Poster
![Project Poster](SURGE_Poster_image.jpg)


