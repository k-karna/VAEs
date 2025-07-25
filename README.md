# Variational Autoencoder (VAE) Variant

From experimentation in ``basic_vae``, we have decided upon

- ``num_epochs = 30``
- ``learning_rate = 25e-4`
- ``latent_dim = 20``
- ``batch_size = 128``

- Basic Variational AutoEncoder (VAE) Output
![Basic VAE](img/basic_vae.png)

- __$\beta$- VAE__ output
![Basic VAE](img/beta_vae.png)

- __Dirichlet- VAE__ output
![Basic VAE](img/dirichlet_vae.png)

Results


- Dirichlet Variational Autoencoder

Total Loss 0.82 Reconstruction Loss: 0.62 KL Loss: 0.19

- __VQ-VAE__ model is trained on CelebA dataset
