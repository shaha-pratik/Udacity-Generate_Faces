# Udacity_face_generation
This project is a part of deep learning nanodegree program at [Udacity](https://www.udacity.com/course/deep-learning-nanodegree--nd101).

## Project Overview

This project, uses generative adversarial networks to generate new images of faces. In this project, you'll define and train a DCGAN on a dataset of faces. Your goal is to get a generator network to generate new images of faces that look as realistic as possible. You'll be using the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train your adversarial networks.

## Project Instruction

1. Clone the repository

```
git clone https://github.com/shaha-pratik/Udacity-Generate_Faces.git
```
2. Install Anaconda or miniconda

This step is not mandotary but it will really good to understand and manage the enviroment in conda. Anaconda is available for Windows, Mac OS X, and Linux. You can find the installers at https://www.anaconda.com/download/ and the installation instructions [here](https://docs.anaconda.com/anaconda/install/).

After that you can open the anaconda promt and create the virtual enviroment name `face_generation` and activate as follow:

```
conda create --name face_generation python=3.6
conda activate face_generation
```

For conda cheatsheet can be found [here](https://docs.conda.io/projects/conda/en/latest/user-guide/cheatsheet.html)

3. Install [PyTorch](https://pytorch.org/) and [torchvision](https://pytorch.org/docs/stable/torchvision/index.html) as below

* Linux or Mac:
```
pip3 install torch===1.3.1 torchvision===0.4.2 -f https://download.pytorch.org/whl/torch_stable.html
```

4. After that to install [jupyter](https://jupyter.org/). The jupyter notebook is a web application that allows you to combine explanatory text, math equations, code, and visualizations all in one easily sharable document.
```
conda install jupyter pillow matplotlib numpy pickle
```

5. Go to terminal and type
```
jupyter dlnd_face_generation.ipynb
```
