# autoencoders
PyTorch implementation of:
- Autoencoder (AE)
- Variational Autoencoder (VAE)
- Vector-Quantized Variational Autoencoder (VQ-VAE)
- Vector-Quantized Variational Autoencoder2 (VQ-VAE2)


## Conda setup and running vq-vae

```
base$ conda create -n autoencoders python=3.11.9
base$ conda activate autoencoders
autoencoders$ conda install -y pytorch torchvision cpuonly -c pytorch
autoencoders$pip install -q "numpy<2.0"
autoencoders$ conda install -y scipy opencv matplotlib six
```

