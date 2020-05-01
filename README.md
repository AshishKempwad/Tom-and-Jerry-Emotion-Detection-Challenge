# Tom-and-Jerry-Emotion-Detection-Challenge

We all remember Tom and Jerry and the immense happiness their misadventures brought in our lives. Now you are required to build a model that detects emotions of the characters in a video frame from our most-loved show. Build a model that detects the emotion of the character present in each frame.



The dataset consists of two parameters—

    Frame_ID that indicates the frame of the video
    
    Emotion that categorizes the emotion of the primary character into different labels: angry(0), happy(1), sad(2), surprised(3), or Unknown(4). The number in brackets is the encoding of the emotion.

Assumptions:

1)Path used is Absolute path

2)Python version : Python 3.1

3)Environment : Google colab

4)Backend : Tensorflow backend, keras


Steps:

1)Read the image using cv2.cvtColor

2)Convert the color into grayscale(cv2.COLOR_BGR2GRAY)

3)Resize the grayscled image appropriately

4)Build CNN

5)Train on the training set with images and the coressponding emotions given as labels. Train the models at various epochs and check for which value of epoch it perfoms better(15-20) should be good value of the epochs.

6)Predict the test images on the model built.

7)Convert the predictions into csv.
