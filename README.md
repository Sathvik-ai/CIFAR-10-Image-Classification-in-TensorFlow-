# CIFAR-10-Image-Classification-in-TensorFlow-
The CIFAR-10 dataset initially stores images as (10000 x 3072) arrays. Each 3072-element row represents a 32x32 pixel color image. To suit CNNs, reshape each row to (32 x 32 x 3) for width, height, and color channels. Normalize pixel values to [0, 1] for effective model training.
