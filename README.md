# Flappy Bird with Affectiva & Sound Input
Using sound input and facial recognition, the player will be able to play the game
To play the game, you would need to open two conda terminals 


Implemented Pygame, Conda, Dlib, PyAudio, Threading, OpenCV, Matplotlib

#To compile and run the game in Windows:
For Affectiva (Facial Recognition)
1) Download Anaconda Python3 from: https://www.anaconda.com/distribution/#download-section
2) conda create --name <yourenvname> python=3 
3) conda activate <yourenvname>
4) conda install -c menpo dlib
5) pip install numpy scipy matplotlib scikit-learn jupyter
6) pip install opencv-python
7) pip install opencv-contrib-python
8) Download the shape_predictor_68_face_landmarks.dat file from this github

For Game & Sound Input
1) Download game from https://github.com/sourabhv/FlapPyBird
2) conda install -c anaconda pyaudio 

#To compile and run the game in MacOS:
For Affectiva (Facial Recognition)
1) Download Anaconda Python3 from: https://www.anaconda.com/distribution/#download-section
2) conda create -n <yourenvname> python=3 anaconda
3) source activate <yourenvname>
4) conda install -c menpo dlib
5) pip install opencv-python
6) Download the shape_predictor_68_face_landmarks.dat file from this github

For Game & Sound Input
1) Download game from https://github.com/sourabhv/FlapPyBird
2) conda install -c anaconda pyaudio 
