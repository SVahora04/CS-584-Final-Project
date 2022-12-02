# Importance of Gradients for Detecting Distributional Shifts

### 1. Dataset Preparation

#### In-distribution dataset

Please download [ImageNet-1k](http://www.image-net.org/challenges/LSVRC/2012/index) and place the training data and validation data in
`./dataset/train` and  `./dataset/val`, respectively.

#### Out-of-distribution dataset
[SUN](https://vision.princeton.edu/projects/2010/SUN/paper.pdf), 
[Places](http://places2.csail.mit.edu/PAMI_places.pdf), 
and [Textures](https://arxiv.org/pdf/1311.3618.pdf).

For SUN,Texture and Places 200 images were sampled from the selected concepts for each dataset,


Please put all downloaded OOD datasets into `./dataset/ood_data/`.

### 2. Running the code

Run the test_ood.py file after downloading and placing them in the correct subfolders.