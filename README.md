# Flower Classification Convolutional Neural Network (CNN)

This project involves the creation of a Convolutional Neural Network (CNN) to classify images of flowers into different categories. The model is trained on a dataset containing five classes: daisy, dandelion, rose, sunflower, and tulip.

## Dataset

The dataset used for training the model is organized into categories, with each category representing a type of flower. The images are preprocessed, resized to 224x224 pixels, and converted to the RGB color space.

## Data Preparation

The dataset is loaded and preprocessed using OpenCV and NumPy. The images are converted to float32 format, normalized to the range [0, 1], and then saved as a pickled file (`data.pickle`) for easy access during training.

## Model Architecture

The CNN model is constructed using TensorFlow and Keras. It consists of convolutional layers followed by max-pooling layers to extract features from the images. The final layers include fully connected (dense) layers for classification. The model is compiled using the Adam optimizer and sparse categorical crossentropy loss.

## Training

The model is trained on the prepared dataset with 90% of the data used for training and 10% for testing. The training process is run for 15 epochs with a batch size of 80. The trained model is saved as `mymodel.keras`.

## Testing and Evaluation

The trained model is loaded, and its performance is evaluated on the test set. The evaluation includes metrics such as accuracy. Additionally, predictions are visualized on a sample of test images, showing both the actual and predicted flower categories.


![image](https://github.com/Poojan38380/Flower-Classification-Convolutional-Neural-Network/assets/119067163/dd2d2e30-f902-43b4-ac45-37dad4c68513)

# It will take a lot of RAM(just warning)
![Screenshot 2024-02-05 190643](https://github.com/Poojan38380/Flower-Classification-Convolutional-Neural-Network/assets/119067163/cf2d9bda-9836-4620-b800-c85c74f12f4a)

