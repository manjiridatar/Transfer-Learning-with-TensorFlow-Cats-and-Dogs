## Transfer Learning using pretrained MobileNetV2 and TensorFlow 2 - The Dogs vs Cats dataset

Our goal is to classify images of cat and dogs using the principle of transfer learning from a pre-trained model (in this case we will use MobileNetV2 which is pretrained on ImageNet dataset containing 1.4 million images and 1000 classes) using tensorflow's functional API. The lower layers of the pre-trained model contained generic features learned that can be applied to a specific task.

We will use the [Dogs vs Cats dataset](https://www.kaggle.com/c/dogs-vs-cats/data), which was used for a 2013 Kaggle competition. It consists of 25000 images containing either a cat or a dog. We will only use a subset of 600 images and labels. The dataset is a subset of a much larger dataset of 3 million photos that were originally used as a CAPTCHA (Completely Automated Public Turing test to tell Computers and Humans Apart), referred to as “Asirra” or Animal Species Image Recognition for Restricting Access.

J. Elson, J. Douceur, J. Howell, and J. Saul. "Asirra: A CAPTCHA that Exploits Interest-Aligned Manual Image Categorization." Proceedings of 14th ACM Conference on Computer and Communications Security (CCS), October 2007.
