1) video of results
2) explain learning rates
3) explain parameters

This is the outcome of the 64x64 iamge size:
![64Image](https://github.com/user-attachments/assets/10ecdcbd-dc70-4262-bd9c-3ad4b352d9a6)


This is the loss during our 128x128 image size:
![128Loss](https://github.com/user-attachments/assets/557aba6d-34be-43b1-b442-b62ebd200bbd)

Major note is that our learning rate for the generator is 0.002 and for the discriminator is 0.00005.
These values are important because it allows for the generator to catch up to the discriminator and it shows of the spike in the beginning.

Our parameters for this GAN in the Conv2d is (in, out, kernel = 4, stride = 2, padding = 1)
This is because we want the discriminator to condence or generator to expand the images for the GAN.

GAN Resources:
Pytorch
https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html

DATASETS:
Pokemon dataset
https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types?select=images
https://www.kaggle.com/datasets/christofferms/pokemon-with-stats-and-image?select=images

Secondary set of pokemon
https://www.kaggle.com/datasets/hlrhegemony/pokemon-image-dataset

Emoji dataset
https://www.kaggle.com/datasets/waqi786/emoji-trends-dataset


Current Dataset : Cartoon Faces
https://www.kaggle.com/datasets/brendanartley/cartoon-faces-googles-cartoon-set?select=cartoonset100k_jpg
