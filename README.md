Video Pre-processing
•
The videos are divided into 75 frames.
•
The frames are combined to create a gif of the video.
Model Architecture
•
CNN:
•
Applied conv3d, ReLU activation layer, and max pool 3.
•
Bidirectional LSTM:
•
Two bidirectional LSTM layers are applied.
•
Bidirectional LSTM is a type of recurrent neural network that processes the input in both forward and backward directions. This allows the model to capture temporal information from both past and future contexts.
•
Dropout layers are applied
•
Softmax activation function is applied.
Training
•
The processed gif input is given to TensorFlow for training.
•
The model is trained using 200 videos each of 3 speakers (2 being male and 1being female)
•
The model is trained for 100 epochs.
