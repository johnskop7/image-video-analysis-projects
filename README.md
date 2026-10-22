# Image and Video Analysis Projects

Two coursework projects developed for the **Image and Video Analysis** course at the **National Technical University of Athens (NTUA)**. The repository covers both classical multi-scale image processing and deep-learning methods for image classification.

> The original laboratory handouts are intentionally **not included**. The project descriptions below are independently written summaries of the work performed. A referenced IEEE paper is cited rather than redistributed.

## Projects

### 1. Gaussian & Laplacian Image Pyramids

A classical image-processing project focused on multi-resolution image representations and the ideas introduced in Burt and Adelson's *The Laplacian Pyramid as a Compact Image Code*.

Main topics include Gaussian generating kernels, image reduction and expansion, Gaussian and Laplacian pyramids, image reconstruction, entropy analysis, coefficient quantization, and experiments on grayscale and RGB images.

See **project-1-laplacian-pyramids/**.

### 2. CNN Image Classification & Transfer Learning

A deep-learning project using a subset of CIFAR-100 to compare classical CNN architectures with a custom model and transfer-learning approaches.

Main topics include LeNet, AlexNet, VGG, custom CNN design, F1-score evaluation, dropout, data augmentation, transfer learning with VGG19 and EfficientNetB0, partial fine-tuning, and scalable TensorFlow input pipelines.

See **project-2-cnn-image-classification/**.

## Repository structure

    .
    ├── README.md
    ├── .gitignore
    ├── requirements.txt
    ├── project-1-laplacian-pyramids/
    │   ├── README.md
    │   └── image_video_analysis_1st_lab.ipynb
    └── project-2-cnn-image-classification/
        ├── README.md
        └── image_video_analysis_2nd_lab.ipynb

## Technologies

Python, Jupyter Notebook / Google Colab, NumPy, SciPy, scikit-image, OpenCV, Matplotlib, TensorFlow and Keras.

## Academic and copyright note

These notebooks contain the student's implementations, experiments, observations and answers. Staff-written exercise handouts are excluded from the repository, and copied assignment instructions inside the notebooks have been replaced by short original section descriptions.

The first project references P. J. Burt and E. H. Adelson, **“The Laplacian Pyramid as a Compact Image Code,”** *IEEE Transactions on Communications*, 1983. The paper itself is not redistributed here.
