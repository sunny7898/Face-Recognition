# Face-Recognition
1. Collecting Dataset
The first step before training any model is collecting the dataset.
In the jupyter file uploaded I have used cv2 for the same - it uses the camera of the laptop to take pictures of your face and store them in the directory specified.
I had collected dataset for my face and My friend's Face i.e. 2 classes and after collecting 1000 images for each , then manually splitted it into 2 folders - Train and Test

2. Training Model
After the collection of dataset , pre-trained model is used - of which all the convolution layers are freezed and new dense / fully connected layers are added which are then trained for the dataset collected previously.

3. Saving the Model
The trained model is saved is then saved which can loaded at any point of time in any file to predict the results.

4. Predicting Results
You can either use a photo you have or use your camera to predict the face in real time.
Also , whlie predicting since I only had two files so I wrote a simple if else condition but in case of more classes the python cade can be modified.

For using this Repository, Simply download this repository and Change all the directories present in the code with the directory you downloaded these files.
