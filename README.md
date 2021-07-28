# **Emotion Detection**
## **Requirements**
1. Python 3.7
2. OpenCV
3. Mediapipe

## **Installation**
1. Clone the repository and install locally
2. Install Jupyter Notebooks - [Click here for download instructions](https://jupyter.org/install)
3. Start a Jupyter Notebook session in the project folder
4. Open the file `EmotionDetection.ipynb`

## **How to Run the Program**
1. Start by running each cell
2. DO **NOT** run the following cells unless you want to either add more classes(emotions) or retrain the data with a completely new set of images
![image](https://user-images.githubusercontent.com/41366297/127317145-c64c140d-6fec-4620-a197-426ce6209216.png)
![image](https://user-images.githubusercontent.com/41366297/127317215-a13b4d31-0f14-4e49-8813-7f1d931efdf0.png)

3. Continue running **each** and **every** cell from then onwards
4. In the following cell, you can change the `filename` variable for the audio file and the path to the zoom recording in `cap = cv2.VideoCapture()`

#### **NOTE: PLEASE ONLY ENTER A .wav FILE FOR THE AUDIO**
#### **NOTE: THE PROGRAM ONLY WORKS IN SPEAKER-VIEW RECORDINGS AND NOT GALLERY-VIEW**

## **Features**
1. Detects the following emotions
  *Happy
  *Sad
  *Attentive
  *Distracted
  *Sleepy
2. Shows the average attention span during the meeting
3. Shows the most prominent emotion in the meeting
4. Shows whether a people were sleepy, if so, they were to see the average drowsiness time and recieve tips
5. Exports the transcript of the meeting to a file called `transcript.txt`
6. Shows a short summary of the meeting

## **Project Demo(Beginner Video)**
For Demo Video, click [here](https://drive.google.com/file/d/1Ctw58PXmBFYUYwe0UvQyLl4Jj2_s_CFM/view?usp=sharing)

## **References**
1. StackOverflow
2. Github
3. https://geeksforgeeks.org
4. https://towardsdatascience.com
5. [Mediapipe Docs](https://google.github.io/mediapipe/solutions/holistic.html)
6. Youtube
