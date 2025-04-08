<h1 align="center">
  <b>Generative Adversarial Networks (DeepConvGAN)</b><br>
</h1>

<p align="center">
    <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-3.10-ff69b4.svg" /></a>
    <a href= "https://pytorch.org/">
    <img src="https://img.shields.io/badge/PyTorch-1.3-2BAF2B.svg" /></a>
    <a href= "https://github.com/baohuy11/Variational-autoencoder/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-Apache2.0-blue.svg" /></a>
</p>

A simple tutorial of Generative Adversarial Networks (DeepConvGAN) models. This repository contains the implementations of following GAN families.


* [DEEP_CONVOLUTIONAL_GENERATIVE_ADVERSARIAL_NETWORKS](https://arxiv.org/pdf/1511.06434) (Goodfellow, I., Pouget-Abadie, J., Mirza, M., Xu, B., Warde-Farley, D., Ozair, S., Courville, A., & Bengio, Y. (2014). Generative Adversarial Networks (arXiv:1406.2661))


# Requirements
```bash
pip install -r requirements.txt
```

# How-to-use
simply run the <file_name>.ipynb files using jupyter notebook.

# Experimental Results
## Deep Convolutional Generative Adversarial Network (DCGAN)
- Trained on animefacedataset for 100 epochs

- Training data

![Training_data](./assets/train.png) 

- Random noise data

![Random_noise](./assets/random_noise.png)

- Generated images

![Generated_images](./assets/gen_img.png)

- Generator and Discriminator Loss

![Loss](./assets/gen_dis_loss.png)

- Training and generated data

![Data_comparision](./assets/train_gen_img.png)
