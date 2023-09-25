# Variational Autoencoder

This is a Generative AI model that creates never-before-seen images. The Variational Autoencoder (VAE) is comprised of two components: and encoder and a decoder.

The encoder will transform the input images into a lower dimension latent space, from which the decoder attempts to reconstruct the original image. This has useful applications for both Generative AI and denoising techniques. The VAE is trained by passing images through the architecture, with better reconstructions yielding lower loss. After the model is trained, feeding random noise to the decoder will create an output image that looks like one from the original training dataset.

I trained this VAE on the classic MNIST handwritten digits dataset. Below we can see some of the model outputs

## 100 Randomly Generated Images

![generated_samples_final](https://github.com/jakesanghavi/Variational_Autoencoder/assets/57878447/e341039b-ba5c-4095-b5f4-46b0118d2980)

## Real/Reconstructed Images Pairs (Real on Top, Reconstructed on Bottom)

![real_recon_pairs_final](https://github.com/jakesanghavi/Variational_Autoencoder/assets/57878447/50a71a4f-c28e-4499-89ab-761a0a640e6b)

## Image Interpolations (One Row Per Interpolation)

![interpolations_final](https://github.com/jakesanghavi/Variational_Autoencoder/assets/57878447/a66fdb9f-27ea-47d8-998b-057e292e9906)
