**Classification of various military aircraft from satellite imagery using neural networks:**

The dataset for this project consists of satellite imagery of 9 types of American Military Aircraft, and of plain land; making it a total of 10 classes to be classified using the neural network models. The dataset was obtained from American military bases throughout the world and is comprised of 6300 images (approximately 620 – 640 images per class). To account for abstraction, the dataset has been augmented. Each image was taken and n number of images with different rotations, zoom level and horizontal flips was produced. 80% of the data was used for training the model, and 20% of the data was used for testing.

![image](https://github.com/Sumukh-Shadakshari/Classification-of-military-aircraft-in-satellite-imagery/assets/131502591/3ed4549c-eef3-4554-9eb4-66e8f19a8ea8)

2 Models: A Convolutional Neural Network and a DenseNet Model were implemented. Pruning of both the models was also done.

**Results**

CNN:

• Training Accuracy of CNN: 94.66%

• Testing Accuracy of CNN: 92.65%


DenseNet:

• Training Accuracy of DenseNet: 97.52%

• Testing Accuracy of DenseNet: 87.35%


Results of implementing Unstructured pruning with sparsity set to 50%:

CNN

• Training accuracy: 98.84%

• Testing accuracy: 96.65%

Densenet:

• Training accuracy: 82.69%

• Testing Accuracy: 43.22%
