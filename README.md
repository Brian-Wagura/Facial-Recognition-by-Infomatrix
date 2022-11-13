# Facial-Recognition-by-Infomatrix
This is a 4th year group project by Group F submitted to Mr Mokodir, Decision Support Systems Lecturer.

# Title: Face Recognition Program

# Objective: To build a face recognition program that does not gender assasinate but detects the gender of a person just by scanning their face

# Dataset
This are the female and male subfolders in the datasets directory containing more than 100 pictures of female and male face pictures in each 
respective subdirectory.
  
# About the project
This project classifies faces according to their gender; either Female or Male.
Convolutional Neural Networks are used to build the model.
It uses opencv-python to video capture and the gender is predicted by the model.
A squarebox is displayed predicting if either the person is female or male.
By showing the camera a picture, the program will also predict if either the picture displayed is male or female

# How you test
-Clone the repository and change directory into the folder:
 git clone https://github.com/wagura-droid/Facial-Recognition-by-Infomatrix.git
-Install virtual environment:
 sudo apt install python3.10-venv
-Create virtual environment
 python3 -m venv <virtualenvname>
-Activate virtual environment:
 source <virtualenvname>/bin/activate
-Install Dependencies
 pip install -r requirements.txt
-Run the program
 python3 GenderClassification.py
  
# Visualization
Inside the screenshots folder.

