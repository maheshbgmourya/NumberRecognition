# NumberRecognition
## MNIST Digit Classification using Keras
This repository demonstrates a neural network-based approach to classify handwritten digits from the famous MNIST dataset using Keras, a high-level neural networks API running on top of TensorFlow. The project's goal is to train a deep learning model capable of accurately recognizing digits from 0 to 9.

## Procedure 
1. *Dataset Loading*: The MNIST dataset is loaded using Keras, consisting of 60,000 training images and 10,000 test images, each of size 28x28 pixels.  
2. *Data Preprocessing*: Images are reshaped and scaled, and labels are one-hot encoded.  
3. *Model Architecture*: A neural network model with two layers is created using Keras.   
4. *Model Compilation*: The model is compiled using the rmsprop optimizer and categorical crossentropy loss.   
5. *Model Training*: The model is trained for 10 epochs with a batch size of 128.   
6. *Model Evaluation*: After training, the model's performance is evaluated on the test dataset and the predictions and actual labels are also shown.
