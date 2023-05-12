# NetSat: Network Saturation Adversarial Attack

**NOTE:** This is a repository with methods, instructions and examples on how to use the components created for the purpose of paper **"NetSat: Network Saturation Adversarial Attack"**. We provide implementation of the vital software components and methods used in the study (**we plan to release our repository upon acceptance**). All of the methods are implemented  in such a way as to make them as flexible as possible not only for the easy reproduction of our experiments but hopefully also for other potential studies of other researchers. We made sure to add comments and guidelines on how to use our methods. Note, that we use only some tiny examplary data (that are compatible with the freely available datasets used in the study) just to show the operation od the notebooks and to make the use of our materials easy for other researchers. 

The repository includes an example on how to (1) generate adversarial samples with our original method - NetSat/SignedNetSat and (2) test the harmfullness of the adversarial attacks in terms of the semantic damage with our Dissimilarity Metric, DM (or after a slight modification - the semantic accuracy of the object recognition network). We provide 2 jupyter notebooks: with a single image example and with a sample dataset. We use large pre-trained  CNN models from keras (https://keras.io/api/applications/). The code can be used to reproduce the results presented in paper **"NetSat: Network Saturation Adversarial Attack"**. 

We present our methods via jupyter notebooks, but we also provide an HTML version of the notebooks.

In our paper, we used three networks krom Keras Application (https://keras.io/api/applications/):
* Xception
* MobileNetV2
* ResNet50V2

Keras provides crafted preprocessing functions for these models, so one can use them to make their data compatible these models. At Keras Application, one can also find the docs regarding these models (required image size etc.). We use the ImageNet weights for these models.

The following Python libraries have to be installed for the example to work correctly:
* NumPy - version 1.23.2
* TensorFlow (+ Keras) - version 2.10.0
* Pandas - version 1.4.2
* SciKit-learn - version 1.1.2
* glob2 - version 0.7
* Pillow - version 7.2.0
* matplotlib - version 3.4.3

We used NIPS 2017 Adversarial Attacks and Defenses Competition (https://github.com/cleverhans-lab/cleverhans/tree/master/cleverhans_v3.1.0/examples/nips17_adversarial_competition), but we also provide a tiny dataset of our own to test the notebook operation correctness (it can be replaced with the original NIPS17 dataset with a slight code modification regarding the image format).

=======
# NetSat-NetworkSaturationAttack
Code that can be used to perform NetSat attacks.
>>>>>>> 6fc045afd577079b5684e3e9ad1a0ae8cf156f5a
