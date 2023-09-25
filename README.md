# Identifying Dog Breeds from Images: A Deep Learning-Based Approach
The notebook shows the code for multi-class classification of images for 120 dog breeds, for the dataset taken from Kaggle: [Dog Breed Identification](https://www.kaggle.com/competitions/dog-breed-identification/overview). 

Classification was implemeted using the pre-trained Deep Convolutional Network VGG16 on augmented image sets (Rotation, Colour Jitter, Horizontal Flip and Crop). The accuracy of VGG16 on the following images sets is shown in the table below:

| Transformation applied | Training Accuracy | Validation Accuracy | Test Accuracy |
| --- | --- | --- | --- |
| Normalisation | 77.30% | 63.36% | 62.13% |
| Normalisation + Rotation | 55.58% | 52.98% | 51.96% |
| Normalisation + Colour Jitter | 77.47% | 61.89% | 66.63% |
| Normalisation + Horizontal Flip | 76.23% | 60.37% | 67.42% |
| Normalisation + Crop | 89.44% | 64.43% | 59% |
| All Transformations | 59.66% | 57.09% | 56.85% |
