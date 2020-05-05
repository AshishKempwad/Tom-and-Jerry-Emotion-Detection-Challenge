# Tom-and-Jerry-Emotion-Detection-Challenge
🕵️ Introduction

We all remember Tom and Jerry and the immense happiness their misadventures brought in our lives. Now you are required to build a model that detects emotions of the characters in a video frame from our most-loved show. Build a model that detects the emotion of the character present in each frame.
💾 Dataset

The dataset consists of two parameters—

    Frame_ID that indicates the frame of the video
    Emotion that categorizes the emotion of the primary character into different labels: angry(0), happy(1), sad(2), surprised(3), or Unknown(4). The number in brackets is the encoding of the emotion.

📁 Files

    train.csv - (1941 samples) File that should be used for training by the user.
    test.csv - (275 samples) File that will be used for actual evaluation for the leaderboard score.Note:- This is not the final test set. -train.zip - Contains the images corresponding to train.csv file -test.zip - Contains the images corresponding to test.csv file

🚀 Submission

    Prepare a csv containing header as emotion and predicted emotion as 0/1/2/3/4 with name as submission.csv.
    Sample submission format available at ./data/sample_submission.csv.

Make your first submission here 🚀 !!
🖊 Evaluation Criteria

During evaluation F1 score and Accuracy will be used to test the efficiency of the model

📚 References

    https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html
    https://www.analyticsvidhya.com/blog/2019/10/building-image-classification-models-cnn-pytorch/

    
    
    

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
