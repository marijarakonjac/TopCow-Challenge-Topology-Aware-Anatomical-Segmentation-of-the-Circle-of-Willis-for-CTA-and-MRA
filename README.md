# TopCoW Challenge: Topology Aware Anatomical Segmentation of the Circle of Willis

This repository contains the implementation of a deep learning solution for segmenting and analyzing the vascular architecture of the **Circle of Willis (CoW)** from 3D angiographic images obtained through CT and MRI technologies.

### Project Background:
The **Circle of Willis** is an anastomotic network of arteries connecting the anterior and posterior circulations of the brain, as well as the left and right hemispheres. The vascular architecture of the Circle of Willis is directly related to the occurrence and severity of strokes and aneurysms, making it of significant clinical importance. Assessing the anatomy of this network from medical angiographic images is a time-consuming and complex task, requiring expert knowledge.

### Problem Statement:
There is a need for an efficient and automated tool that can segment and analyze the angiographic architecture of the Circle of Willis. This project addresses that need by proposing the use of deep learning for automatic segmentation.

### Approach:
In this work, we used the **UNet architecture**, which is an autoencoder-based neural network architecture, for segmenting the vessels of the Circle of Willis. The challenge involves topologically-aware segmentation, where the extracted blood vessels need to retain the underlying anatomical topology.

### Key Results:
- **Dice coefficient:** Over **0.83** on the test set, indicating excellent segmentation performance.
- **Target**: To accurately characterize the vascular structure by preserving both topological and geometric variability of the Circle of Willis.

### Technologies Used:
- **Deep Learning**: UNet architecture
- **Metrics**: Dice coefficient
- **Image Data**: 3D angiographic images from CT and MRI

### Acknowledgments:
This project was developed as part of the Biomedical Image Analysis course at School of Electrical Engineering, University of Belgrade. Special thanks to the course instructor and the GrandChallenge platform for providing the TopCoW challenge data.
This project was completed in collaboration with Marija Brkić.
