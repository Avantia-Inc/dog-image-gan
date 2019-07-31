# dog-image-gan

Creates dog images using a machine learning generative adversarial network (GAN)

Build and run docker image with:
```
docker build . -t avantia/gan:0.0.1
docker run --gpus all -v $(realpath .):/mnt avantia/gan:0.0.1 python /mnt/number-gan.py
```

## Requirements

* docker >= v19.03
* nvidia-container-toolkit or nvidia-container-runtime (https://github.com/NVIDIA/nvidia-container-runtime)

### Install requirements for Arch-based OSes
```
pacman -Sy docker nvidia-container-toolkit
```
