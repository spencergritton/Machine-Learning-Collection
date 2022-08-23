# Progressive Growing GAN (ProGAN)
A jupyter notebook based implementation of the ProGAN paper from Karras et al. ProGAN proposes a new methodology of unsupervised photo generation which slowly scales up the generator and critic architectures during training. Notably, ProGAN is utilized in the more popular StyleGAN paper which generates incredibly realistic images of human faces. This paper implemented the following:
- Progressive Growing
- Pixel Normalization
- Minibatch Standard Deviation
- Equalized Learning Rate
- Created the CelebA-HQ dataset

This implementation, like the original paper, generates faces in an unsupervised manner from the CelebA-HQ dataset. Unlike the paper, images generated here are only 128x128 as opposed to 1024x1024 due to computational constraints.

# Results

<img width="60%" src="../../Photos/GANs/ProGAN.jpeg" />


# Paper
## Abstract
We describe a new training methodology for generative adversarial networks. The key idea is to grow both the generator and discriminator progressively: starting from a low resolution, we add new layers that model increasingly fine details as training progresses. This both speeds the training up and greatly stabilizes it, allowing us to produce images of unprecedented quality, e.g., CELEBA images at 10242. We also propose a simple way to increase the variation in generated images, and achieve a record inception score of 8.80 in unsupervised CIFAR10. Additionally, we describe several implementation details that are important for discouraging unhealthy competition between the generator and discriminator. Finally, we suggest a new metric for evaluating GAN results, both in terms of image quality and variation. As an additional contribution, we construct a higher-quality version of the CELEBA dataset.

## Citation
```
Karras, Tero, et al. "Progressive growing of gans for improved quality, stability, and variation." arXiv preprint arXiv:1710.10196 (2017).
```
