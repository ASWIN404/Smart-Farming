# Smart-Farming
This project focuses on detecting plant leaf diseases using image data and deep learning. The goal is to help farmers identify diseases early by analyzing visual symptoms on leaf surfaces, which are often the first indicators of crop health problems.

The dataset used for this project is Plantvillage dataset.

Used a Convolutional Neural Network (CNN) trained on a labeled dataset of leaf images containing both healthy and diseased samples. The input images undergo preprocessing steps such as:

Resizing
Normalization
Data Augmentation
Class Label Encoding

These steps ensure the model learns important visual patterns such as color changes, texture irregularities, and shape distortions that commonly occur in infected leaves.

After training and testing, the CNN achieved a validation accuracy of above 90%, showing that deep learning can reliably classify leaf diseases based on simple images. This allows fast and automated disease detection without the need for expert inspection.

Overall, the project demonstrates how AI can support agriculture by improving crop monitoring, enabling early disease diagnosis, and promoting smarter and more efficient farming practices.
