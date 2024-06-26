**Hand Gesture Recognition**
----------------------------------------------------------------------------------------------
This project focuses on developing a hand gesture recognition system using Convolutional Neural Networks (CNNs). The dataset used for training the model is the Leap Gesture Recognition dataset, which contains images of various hand gestures captured from a Leap Motion Controller.

**Dataset Description**
----------------------------------------------------------------------------------------------
The dataset is organized into ten categories, each representing a different hand gesture:

1.Palm (01_palm)

2.L (02_l)

3.Fist (03_fist)

4.Fist Moved (04_fist_moved)

5.Thumb (05_thumb)

6.Index (06_index)

7.OK (07_ok)

8.Palm Moved (08_palm_moved)

9.C (09_c)

10.Down (10_down)

The dataset is split into training, validation, and testing sets to train and evaluate the CNN model.

**Requirements**
----------------------------------------------------------------------------------------------
.Python 3.x

.NumPy

.PIL (Python Imaging Library)

.Matplotlib

.TensorFlow

.Keras

.scikit-learn

You can install these dependencies using pip: pip install numpy pillow matplotlib tensorflow keras scikit-learn

**Usage**
----------------------------------------------------------------------------------------------
Clone the repository or download the source code. Set up your Python environment with the required dependencies. Run the provided Python script (hand_gesture_recognition.py) to train and evaluate the CNN model.

**File Structure**
----------------------------------------------------------------------------------------------
hand_gesture_recognition.py: Python script for training the CNN model. README.md: This file containing project information and instructions.

LICENSE: License information for the project (if applicable). requirements.txt: List of dependencies for easy installation.

**Training the Model**
----------------------------------------------------------------------------------------------
To train the CNN model, run the following command: python hand_gesture_recognition.py The script will preprocess the dataset, build and train the CNN model, and evaluate its performance on the test set.

**Results**
----------------------------------------------------------------------------------------------
After training and evaluation, the model's accuracy on the test set is displayed.

**License**
----------------------------------------------------------------------------------------------
This project is licensed under the MIT License.
