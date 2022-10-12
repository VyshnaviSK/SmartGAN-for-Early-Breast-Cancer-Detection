# SmartGAN-for-Early-Breast-Cancer-Detection

The prominent rise in Machine Learning (ML) and Computer Vision
has led to a quite improvement in detecting breast cancer based on mammograms.
But training the existing ML model from scratch requires many
labeled data, such as mammographic tumor images. Since the performance
of a classifier requires more training data, there is a need to create
new training images, such as an image augmentation process called Generative
Adversarial Network (GAN). But some existing works point out several
common failure modes in GAN. Some failures happen due to the random
use of different types of GAN where the discriminator is too good, but
generator training fails due to vanishing gradients. Due to this, an optimal
discriminator cannot provide enough information for the generator to
make progress. Thus, selecting the best GAN model for the given scenario
can solve this problem. Hence, this paper aims to develop a smart, efficient,
and computational classification model given a limited imbalanced
dataset of mammograms containing malignant breast cancer and benign
non-cancerous images. This work proposes a novel Smart GAN architecture
for generating authentic and diverse images for primary datasets
such as the Mammographic Image Analysis Society (MIAS). Smart GAN
smartly chooses the best GAN model to augment the primary dataset using
reinforcement learning. Then, the suitable convolutional neural network
is used to perform classification on the augmented dataset. Results
show that Smart GAN increases the detection performance by achieving
an accuracy of 89.62% against 79.30% without augmenting the data. Also,
this paper makes a comparative analysis where Smart GAN outperforms
most of the existing approaches.
