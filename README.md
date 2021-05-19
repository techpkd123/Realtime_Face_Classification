# Realtime_Face_Classification
![image](https://user-images.githubusercontent.com/49801313/118780372-985abf80-b8a9-11eb-874e-06e4fc4b4b41.png)
<h2>Installation instructions</h2>

<h4>Open project in pyCharm or any IDE</h4> 
<h4>First go to project directory</h4> 
<h4>python3 FaceTraining.py to train the models</h4> 
<h4>After that run the Recognition.py file</h4> 
<h4>And webcam opens and classfies the face of the person</h4> 
<hr>                                             </hr>
<h3>To create a complete project on Face Recognition, we must work on 3 very distinct phases:</h3>
<h4>1)Face Detection and Data Gathering</h4>
       <h5>All the data was collected from the dataset provided and manually cleaned the data</h5>
<h4>2)Train the Recognizer</h4>
       <h5>recognizer.train(faces, ids): This will train all the faces with the id's(1 to 15)of the players mentioned and creates a trainer.yaml file </h5>
<h4>3)Face Recognition</h4>
       <h5>we will detect a face, same we did before with the haasCascade classifier. Having a detected face we can call the most important function in the above code:</h5>
       <h5>id, confidence = recognizer.predict(gray portion of the face)</h5>
       <h5>The recognizer.predict(),will take as a parameter a captured portion of the face to be analyzed and will return its probable owner, indicating its id and how much    
           confidence the recognizer is in relation with this match. </h5>
       

<hr>                                             </hr>
