# GANPRM
The repository for training and analyses code for the paper: Generative adversarial learning explains why imagination feels less real as we grow up by Ataol Burak Ozsu, Nora Petrova, Tessa Dekker & Nadine Dijkstra. 

The training codes provide a comprehensive guideline to train WGAN with gradient penalty (Arjovsky et al., 2017; Gulrajani et al., 2017) with the training sets CIFAR-10 and CelebA documented separately.

This repository also contains the codes for the analyses reported in the paper, including Frechet Inception Distance (FID; Heusel et al., 2017) calculation with each layer of AlexNet (Krizhevsky et al., 2012) as the feature space, feature importance calculation per AlexNet layer for discriminator judgments, Centered Kernel Alignment (Kornblith et al., 2016) calculation per AlexNet layer and trained classifier/discriminator and Grad-CAM (Selveraju et al., 2016) implementation.

To run the analyses you would have to have access to the model weights per epoch, which can be acquired from: https://osf.io/q72c9/overview

For any questions, please refer to: a.ozsu@ucl.ac.uk
