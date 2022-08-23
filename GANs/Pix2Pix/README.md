# Pix2Pix
A jupyter notebook based implementation of the Pix2Pix paper from Isola et al. This paper implemented the following:
- BatchNorm
- Dropout
- UNet architecture for generator
- PatchGAN based critic
- Removed common Z latent vector
- Added L1 loss to traditional GAN loss to encourage color and reduce visual artifacts

This implementation applies Pix2Pix to colorizing grayscale images. 

# Results
Legend: Top - Grayscale Input, Middle - Original, Bottom - Colorized Output
<img width="65%" src="../../Photos/GANs/Pix2Pix.jpeg" />


# Citation
```
Isola, Phillip, et al. "Image-to-image translation with conditional adversarial networks." Proceedings of the IEEE conference on computer vision and pattern recognition. 2017.
```