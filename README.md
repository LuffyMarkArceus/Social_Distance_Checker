# Social_Distance_Checker
Shows any social distancing violations from a given video feed, using OpenCV and YOLO Algorithm.

Add the yolo3.weights file to the same folder as the detect.py file,
which can found here: https://drive.google.com/u/0/uc?export=download&confirm=phEB&id=1I92QB0ifKoEOZcUq6gAfay-o4Tjw1xTU

Files:

output.avi : The final output files saved by 'detect.py'

detect.py  : The actual python code file which calculates the social distance between people in the input given.

yolov3.cfg : config file for YOLO V3 algorithm

yolov3.weights : Weights file, this contains the hyperparameter data for our model.

Folder:
data : place input files here, with which you want to test this model.
