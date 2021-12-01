<h1 align="center">
  
  VISION360

</h1>

<h4 align="center">A Stock Market Prediction Web Application<a href="https://github.com/ishaannverma/VoyageCapital" target="_blank"></a></h4>


<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#our-inspiration">Our Inspiration</a> •
  <a href="#technologies-used">Technologies Used</a> •
  <a href="#apis-used">Apis Used</a> •
  <a href="#links">Links</a> •
  <a href="#team">Team</a>
</p>
  <br>
## Problem Statement

There has been a sharp rise in the amount of disruptive and offensive activities in the past decade that makes security a significant concern. Public places like shopping centres, hospitals, banks and even neighbourhoods are increasingly being equipped with CCTVs to guarantee the security of individuals. Since constant observation of these surveillance cameras is a near-impossible task for us human beings, we need a working model that is able to analyse in depth, if the captured activities are anomalous or suspicious, hence the need to automate this process with high precision arises.

## Our Solution

Therefore, to reduce the wastage of time and labour, we have come up with our project VISION 360 that utilizes deep learning algorithms for smart activity detection and other forms of motion detection. One of its many goals is to automatically identify signs of irregularities in real-time. We plan to use different deep learning models to identify and classify various levels of movement in the frame that can raise a detection alert for the situation of a threat, indicating the suspicious activities at an instance of time. The user is required to register on our website using their email ids and then the user can enter a video feed to our server. The website can also be connected to CCTVs, where we extract frames from the captured CCTV recordings which can then be analysed and classified by various trained models. Some of these models include Facial Recognition, Motion Detection, Fire and Activity Detection. In case something out of the normal is detected, a mail alert would be sent to the concerned user. We plan on utilizing tools such as machine learning, deep learning and web development technologies. In today’s world of uncertainty and lurking dangers, choose VISION 360 to help you ensure safety of your space.

## Learning Phases

<strong><ins>Team Member Formation</ins>:</strong>
1. Choosing the field of interest after a series of meetings with the team members.
2. Selecting the appropriate mentor best suited to the technology selected.<br>

<strong><ins>Project Idea Discussion and Synopsis Drafting</ins>:</strong>
1. Project Ideas explored by all the team members.
2. Decided on two project ideas before presenting to our project mentor, Professor Sachin. The ideas were:
    1. Our first idea was a suspicious activity detection system that we wanted to build using various AI models. We read numerous research papers on this to broaden our   knowledge. 
    2. Our second idea was an intelligent suggestive system for backpackers.
3. After a thorough research on both the ideas we narrowed our project topic to a Smart Survillance system.

<strong><ins>Discovering Project Requirements</ins>:</strong>
1. Looking onto the existing work in this related field, if done.
2. Deciding the further objectives which can be achieved, and which would add a lot of value to the existing project.
3. We must have datasets for training purposes of our models to be able to predict the required output.
4. Deciding on technology for Deep learning depending on the familiarity of the teammates with the technologies:
5. Natural Language Processing(NLP) using Recurrent Neural Networks(RNN) and LSTM.
6. Tensorflow and Keras framework for training the model.
7. Deciding on technology for frontend and backend for the website(and parallelly learning them during the training phase):
8. Frontend - HTML, CSS, javascript, bootstrap
9. Backend - Flask, Python, Open cv

<strong><ins>Model Implementation</ins>:</strong>
1. Implementation of various models in python using pre-trained dataset.
2. Models were selected after rigorously going through various reasearch papers.

<strong><ins>Frontend</ins>:</strong>
1. Added login, register, contact us and about us pages

<strong><ins>Developing the backend and Integrating with front end</ins>:</strong>
1. Developing the website’s backend using the Flask framework of python.
2. Started integrating the frontend and the backend.
3. Details page added providing information of the recent models used.

<strong><ins>Future Scope</ins>:</strong>
1. We could add more suitable models which can be used for accomplishing different tasks. The added models can be integrated with other models, thus resulting in more functionalities using the same set of models.
2. Performance in terms of speed and computational resources is a major factor to be considered in our whole application. We could possibly look into parallel computing and other better computing options, but this would be a very big task. 
3. If added more customizable by user and better results shown, a mobile application would be very easy to access for the owner and thus could be one of the future prospects.

## Diagrams

<a href = "https://github.com/Vision-360/SE-Submissions/blob/main/Use_Case_Diagram.png"> Use Case Diagram </a>
<br>
<a href="https://github.com/Vision-360/SE-Submissions/blob/main/Activity_Diagram.png">Activity Diagram</a>
<br>
<a href="https://github.com/Vision-360/SE-Submissions/blob/main/README.md">Project Write-Up</a>

## Technologies Used

1. <a href="https://html.com/" target="_blank">HTML</a>    
2. <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank">CSS</a>
3. <a href="https://getbootstrap.com/">Bootstrap</a>
4. Javascript
5. <a href="https://www.python.org/">Python</a>
6. <a href="https://flask.palletsprojects.com/en/1.1.x/">Flask</a>
7. Keras

## Key Features
1. **New User Login:** A new user can login into the website by entering id and password.
2. **User authentication:** Each user will be provided its own username and password and details of the user will be stored in the firebase.
3. **Motion Detection:** Uses an OpenCV function. If the contour is greater than 3200, we draw rectangles around the objects and show that motion has been detected.
4. **Emotion Recognition:** Detects and displays emotions realtime. Uses deepFace.
5. **Face Recognition:** Displays the name of the person realtime
6. **Activity Detection:** It can recognize over 400 activities with 78.4-94.5% accuracy.
7. **Fire Detection:** Detects fire and sends a mail to the concerned user.
8. **Flood Detection:** Detects flooding of area.
9. **Object Detection:** Draws boxes around the objects detected with color of box varying from one class of object to other.
10. **Details Page:** Shows the recent 5 detections made by models.
11. **User Query and Support:** The user can put in queries on the contact us page which will be received directly in the admin email.

## Website Features

Motion Detection<br>
<img src="https://github.com/Vision-360/Vision-360-Project/blob/9c11aad5192252bdedb5070c96c2efdd67987fe8/static/Motion.gif"  width="100%">

## Team Members

1. 19103105 Ananya Gupta 
2. 19103071 Trisha Bassan 
3. 1910110 Nibhrit Garg 
4. 19103090 Divyansh Agarwal 
