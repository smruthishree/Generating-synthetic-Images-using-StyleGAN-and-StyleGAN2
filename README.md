
# StyleGAN and StyleGAN2 Human Image Synthesis

This GitHub repository contains interesting experiments showcasing the capabilities of the pretrained StyleGAN2 network, which was trained on the custom dancer dataset. The images used here are synthetic human images obtained by training on StyleGAN and StyleGAN2 models. The primary dataset used in this project consists of 3,000 high-quality images of dancers in various poses. 

## Dataset
The dataset used for training and experimentation comprises 3,000 high-quality images of dancers in various poses. These images were carefully curated to provide a diverse range of dance movements and body positions. The dataset serves as the foundation for creating synthetic human images with the StyleGAN and StyleGAN2 models.

### Data Preprocessing
In the data preprocessing stage, actual images of dancers are used as input. To facilitate experimentation, fake images are created from the pretrained StyleGAN2 model. These fake images are generated using the learned features and latent space of the model. The combination of real and synthetic images allows for a wide range of experiments.

## Experiments
### Image Morphing
One of the exciting experiments conducted using the pretrained StyleGAN2 network is the ability to morph or transition between different poses of dancers. This functionality allows for seamless transformations from one dancer pose to another. Some key highlights of this experiment include:

#### Pose Transition
- **Male to Female Dancer**: Using the pretrained StyleGAN2 model, you can smoothly morph a male dancer's pose into that of a female dancer. This demonstrates the flexibility of the model in generating realistic and plausible transitions between different gender presentations.

### Interpolation Images with StyleGAN2
Another fascinating experiment involves generating interpolation images using the StyleGAN2 model. Interpolation involves creating a sequence of images that gradually transition from one pose to another. This can be used to visualize smooth transformations between poses and explore the latent space of the model.

Official Implementations
StyleGAN Official Implementation
StyleGAN2 Official Implementation




#### GAN workflow

![image](https://user-images.githubusercontent.com/74066072/217257825-d4b13ca0-08e6-42b5-bf61-7939a60d6ccf.png)


#### About dataset

![image](https://user-images.githubusercontent.com/74066072/217257569-a0b3c815-70fb-470f-b63a-b3961fceb2f1.png)

#### Fake Human images generated using StyleGAN model

![image](https://user-images.githubusercontent.com/74066072/217258304-e0acdd6f-c44e-4c76-bc01-e6ea9afa7a44.png)
![image](https://user-images.githubusercontent.com/74066072/217258355-d99f173a-de29-4895-9947-046cab80f6c4.png)




