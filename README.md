# Flappy Bird with Affectiva & Sound Input
Using sound input and facial recognition, the player will be able to play the game either through using regular keyboard or through sound input.

To play the game, you would need to open two conda terminals; one for facial recognition and one for the game

Implemented Pygame, Conda, Dlib, PyAudio, Threading, OpenCV, Matplotlib

# To compile and run the game in Windows:
For Affectiva (Facial Recognition)
1) Download Anaconda Python3 from: https://www.anaconda.com/distribution/#download-section
2) conda create --name <yourenvname> python=3 
3) conda activate <yourenvname>
4) conda install -c menpo dlib
5) pip install numpy scipy matplotlib scikit-learn jupyter
6) pip install opencv-python
7) pip install opencv-contrib-python
8) Download the shape_predictor_68_face_landmarks.dat file from this github
9) Download facial.py file from this github
10) Download SHAPE_PREDICTOR_68_FACE_LANDMARKS.DAT from https://github.com/AKSHAYUBHAT/TensorFace/blob/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat

For Game & Sound Input
1) Download flappy.py from this github
2) Download sprites file from this github
3) conda install -c anaconda pyaudio 

# To compile and run the game in MacOS:
For Affectiva (Facial Recognition)
1) Download Anaconda Python3 from: https://www.anaconda.com/distribution/#download-section
2) conda create -n <yourenvname> python=3 anaconda
3) source activate <yourenvname>
4) conda install -c menpo dlib
5) pip install opencv-python
6) Download the shape_predictor_68_face_landmarks.dat file from this github
7) Download facial.py file from this github
8) Download SHAPE_PREDICTOR_68_FACE_LANDMARKS.DAT from https://github.com/AKSHAYUBHAT/TensorFace/blob/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat
  
For Game & Sound Input
1) Download flappy.py from this github
2) Download sprites file from this github
3) conda install -c anaconda pyaudio 

# Data 
1) Download or Create file data.txt, data2.txt from the github
2) Download test.py from the github

Game Source:
https://github.com/sourabhv/FlapPyBird
