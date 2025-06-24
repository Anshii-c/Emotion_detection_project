# Task 1:Emotion Detection through Voice

Creating a machine learning model that can recognize human emotions from audio inputs is the goal of this project.  Using recorded input through an intuitive graphical user interface (GUI) and voice notes that are uploaded, the model is made to only work with **female voices**.

 # The goals:
 Train a model to categorize voice samples into different emotional states, such as neutral, angry, sad, and happy.
 Be sure to use gender filtering:  Voice inputs are exclusively accepted from females.
 Create a graphical user interface (GUI) that facilitates simple interaction, with features like: 📤 Upload voice notes - 🎙️ Record new voice input - 💬  Show the anticipated emotion or ask the user to try again if the voice is not female.

 The audio preprocessing (MFCC extraction, silence removal) is one of the features.
 Logic for gender verification prior to emotion inference
 Emotion prediction display in real time - Simple, clean graphical user interface utilizing `Tkinter`.
 # The dataset
 makes use of training annotated audio datasets (such as RAVDESS and TESS).  Data ought to be gender-labeled or pre-filtered.
 
 ## Rules
 Voice input should take less than four seconds.
 The GUI should give clear status feedback (processing, success, retry) when non-female voices are heard.


