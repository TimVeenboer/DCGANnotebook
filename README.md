## Deep Convolutional Generative Adverserial Network

This repository is largely based on the article from Ian Goodfellow et. al. Generative Adversarial Networks (GAN) emulate a 'two-player adversarial game', where a generative model tries to trick a discriminative model. This discriminative model in turn tries to recognize whether an image has been produced by the generative model or whether it's a real image. 

It's pretty hard to decently train a GAN, since the discriminator and generator have to be pretty even in their capabilities. If the generator overfits, it only generates the same digit over and over. However, if the discriminator is too strong then the generative model learns too little; and therefore produces very low quality digits. There are definitely better models out there, such as CycleGAN and StyleGAN, however this project was solely built to understand the dynamic between the generator and the discriminator. I was also largely interested in just seeing how GANs work and what the underlying mathematics are that make the GAN a working model. I built this model to create fake digits with the MNIST database. The results are pretty decent, but nothing out of the ordinary. This project was purely undertaken as a learning experience.  

Some digits produced by the model in this repository:

![alt text](https://github.com/TimVeenboer/DCGANnotebook/blob/master/customdigits.png)

## References

Goodfellow, I. J., Pouget-Abadie, J., Mirza, M., Xu, B., Warde-Farley, D., Ozair, S., Courville, A., & Bengio, Y. (2014). Generative adversarial networks. ArXiv:1406.2661 [Cs, Stat]. http://arxiv.org/abs/1406.2661

Radford, A., Metz, L., & Chintala, S. (2016). Unsupervised representation learning with deep convolutional generative adversarial networks. ArXiv:1511.06434 [Cs]. http://arxiv.org/abs/1511.06434

Inkawhich, N. (2021). DCGAN Tutorial — PyTorch Tutorials 1.8.1+cu102 documentation. Retrieved 30 April 2021, from https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html
