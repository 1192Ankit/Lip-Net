LipNet: Speech Recognition from Lip Movements
LipNet is a deep neural network designed to recognize speech from lip movements. By leveraging a combination of convolutional and recurrent neural networks, LipNet analyzes sequences of frames from videos of individuals speaking and predicts the spoken words.

Video Pre-processing
Videos are divided into 75 frames.
Frames are combined to create a GIF of the video.
Model Architecture
Convolutional Neural Network (CNN)
Applied 3D convolution (conv3d)
ReLU activation layer
Max pooling (max pool 3)
Bidirectional LSTM
Two bidirectional LSTM layers are applied
Bidirectional LSTM processes input in both forward and backward directions, capturing temporal information from past and future contexts.
Dropout layers are applied to prevent overfitting.
Softmax activation function is used for the output layer.
Training
The processed GIF input is fed into TensorFlow for training.
The model is trained using 200 videos from 3 speakers (2 male, 1 female).
Training is conducted over 100 epochs.
This repository contains the code and resources for LipNet, making it a powerful tool for speech recognition from lip movements.








