# Color Conversion using CNN Auto-encoder

This project utilizes TensorFlow and Keras to showcase a Convolution Neural Network Auto-encoder which is specifically created to add colour to grayscale images. The model is structured with layers for downsampling (convolutional) and upsampling (transposed convolutional). The process involves the following steps:

- Image Preprocessing: Grayscale and color images are resized and normalized.
- Model Architecture: Includes downsampling layers with batch normalization and upsampling layers for reconstruction.
- Training: The model is trained using Mean Absolute Error (MAE) loss for effective learning.
- Visualization: The results are presented by comparing the original colour images, grayscale inputs, and model predictions.

This project serves as a practical example of using deep learning for image-to-image translation tasks in computer vision.


![autoencoder](https://github.com/user-attachments/assets/827d0163-419c-4716-8c67-5ba41d6868c2)
