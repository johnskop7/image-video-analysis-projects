# Project 1 — Gaussian & Laplacian Image Pyramids

This project studies **multi-resolution image representations** using Gaussian and Laplacian pyramids. It is inspired by the classical work of Burt and Adelson on Laplacian-pyramid image coding.

The original course handout and the IEEE paper PDF are not included in this repository.

## Implemented components

The notebook implements construction of the Gaussian generating kernel, low-pass filtering and downsampling, Gaussian-pyramid generation, image expansion, Laplacian-pyramid generation, reconstruction of the original image, coefficient quantization, and support for both grayscale and RGB images.

## Experiments

The implementation is evaluated on standard test images such as **Camera** and **Lena**. The experiments examine the kernel parameter a, pyramid depth, reconstruction quality, entropy at different pyramid levels, entropy-based parameter selection, and the impact of quantization bin size.

The notebook also contains the student's theoretical discussion of entropy, pyramid behaviour and quantization.

## Notebook

**image_video_analysis_1st_lab.ipynb**

## Reference

P. J. Burt and E. H. Adelson, *The Laplacian Pyramid as a Compact Image Code*, IEEE Transactions on Communications, 1983.
