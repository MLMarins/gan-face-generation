# gan-face-generation

This project is part of Udacity Deep Leaning Nanodegree repo.

# Goal

In this project, we'll defined and trained a DCGAN on a dataset of faces. The goal of this project is to get a generator network to generate new images of faces that look as realistic as possible.
The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. 


The model is trained on the CelebFaces Attributes Dataset (CelebA):
![Alt text](../gan-face-generation/assets/processed_face_data.png?raw=true "Optional Title")
<img src="./gan-face-generation/assets/processed_face_data.png" alt="Screenshot" style="max-width:100%;">


The output is new human faces such as:
![Alt text](../gan-face-generation/assets/output.png?raw=true "Optional Title")


# Recommended next steps - improvements
- Increase number of epochs. I only run 2 because I was on CPU. 

- Create a deeper model and use it to generate larger (say 128x128) images of faces.
- Read existing literature to see if you can use padding and normalization techniques to generate higher-resolution images.
- Implement a learning rate that evolves over time as they did in this https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix
- See if you can extend this model and use a CycleGAN to learn to swap different kinds of faces. For example, learn a mapping between faces that have and do not have eye/lip makeup, as they did in https://gfx.cs.princeton.edu/pubs/Chang_2018_PAS/Chang-CVPR-2018.pdf

