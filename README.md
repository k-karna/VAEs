﻿# Variational Autoencoder (VAE) Variant

From experimentation in ``basic_vae``, we have decided upon these few: 
1. ``num_epochs = 30``, 2. ``learning_rate = 25e-4``, 3.``latent_dim = 20`` and 4. ``batch_size = 128``

### Results

| VAE Variant | Parameters | Total Loss | Reconstruction Loss | KL-D Loss | Training Time |
| ----| ----- |-----| ---- | -------- | ---- |
| General VAE | 310, 504 | 97.72 | 73.21 | 24.51 | 20 min 26s |
| Beta VAE | 236, 740 | 131.97 | 94.51| 12.49 | 16 min 49s |
| Dirirchlet VAE | 284, 405 | 0.92 | 0.77 | 0.15 | 21 min 20s |
| VQ-VAE | 299,985 | 0.9079| 0.0012 |``VQ-Loss``: 0.9067 | 61 min 44s|
| VQ-VAE ( ``celebA``) | 303,187 | 0.0751 |0.0039 | ``VQ_Loss``: 0.0713 | 71 min 23s (TPU) |
