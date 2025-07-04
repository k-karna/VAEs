### Variational Autoencoder (VAE) Variant

- Variational Autoencoder

| Exp No. | Epochs |Latent Dimension | Learning Rate | Total Loss | Reconstruction Loss | KL-D Loss |
| ----| ----- |-----| ---- | -------- | ---- | ----- |
| 1 | 30 | 02 | 1e-3 | 145.51 | 139.26 | 6.25 |
| 2 | 30 | 10 | 1e-3 | 100.56 | 81.06 | 19.50 |
| 3 | 30 | 20 | 1e-3 | 98.26 | 73.35 | 24.91|
| 4 | 30 | 20 | 25e-4 | 97.85| 73.25| 24.60 |
| 5 | 30 | 10 | 25e-4 |100.98 | 81.75 |19.23 |
| 6 | 50 | 10 | 25e-4 | 99.71 | 80.36 | 19.35 |
| 7 | 50 | 20 | 25e-4 | 96.80 | 72.33 | 24.47 |

- Beta Variational Autoencoder (Using same ``Latent Dimension`` of $20$ from ``basic_vae``)

| Exp No. | Epochs | Learning Rate | __Beta__ $\beta$ | Total Loss | Reconstruction Loss | KL-D Loss |
| ----- | ----- | ----- | -----| -----| -----| -----|
| 1 | 30 | 25e-4 | __4.0__ | 143.04 | 102.96 | 10.02 |
| 2 | 30 | 25e-4 | __8.0__ | 172.95 | 132.52 | 5.05 |
| 3 | 30 | 25e-4 | __6.0__ | 160.44 | 118.76 | 6.95 |
| 4 | 30 | 25e-4 | __3.0__ (samples from latent space - best)| 132.12 | 94.44 | 12.56 |  
| 5 | 30 | 25e-4 | __0.8__ |  92.75 | 70.77 | 27.47 |
| 6 | 30 | 25e-4 | __0.5__ | 83.60 | 66.89 | 33.42 |

- Dirichlet Variational Autoencoder
