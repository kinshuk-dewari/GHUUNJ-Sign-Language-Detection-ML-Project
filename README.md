# GHUUNJ 
A Realtime Sign Language Detection project using Action Recognition [ LSTM Deep Learning Model ]

<h3>Some Python's helpful shortcuts:</h3>
to install a requirements.txt file : pip install -r requirements.txt <br>
to make a requirement.txt file : pip freeze > requirement.txt<br><br>

## You can install all these required dependencies through: 
    pip install tensorflow opencv-python mediapipe sklearn matplotlib        
## Or Download the requirement.txt file in the Project folder and then Use this command : <br><br>
    pip install -r requirements.txt 




<h2>GOALS</h2>
1.Extractholistic points,<br>
2.Train an LSTM dl model,<br>
3.Make real-time predictions using sequences.<br>

<h2>HOW IT WORKS:</h2>
1.	Collect key points from media pipe holistic, <br>
2.	Train a deep neural network with LSTM layers for sequences,<br>
3.	Perform real-time sign language detection using OpenCV,<br>

<h2>WORKFLOW</h2>
01.	Import and install dependencies,<br>
02.	Keypoints using MP Holistics,<br><br>
<img src="images/landmarkings.png" width="32" height="32" style="width:500px;height:400px" />
03.	Extract keypoint value,s<br>
04.	Setup folders for collection,<br>
05.	Collect keupoints values for training and testing,<br>
06.	Preprocess data and create labels and features,<br>
07.	Build and train LSTM Neural network,<br><br>
<img src="images/training.png" width="32" height="32" style="width:2000px;height:800px" />
08.	Make predictions,<br>
09.	Save weights,<br>
10.	Evaluate using confusion matrix and accuracy,<br>
11.	Test in real time .<br>

# Predicting Hello 
<img src="images/hello.png" width="32" height="32" style="width:500px;height:400px" />

# Predicting Thanks 
<img src="images/thanks.png" width="32" height="32" style="width:500px;height:400px" />

# Predicting I Love You
<img src="images/iloveyou.png" width="32" height="32" style="width:500px;height:400px" />




