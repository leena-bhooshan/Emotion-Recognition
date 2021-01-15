# Emotion-Recognition
It is a Emotion Recognition Application executed using Flask. Emotions such as Happy, Sad, Surprised, Angry, etc. are detected using an emotion detection deep learning model.

The emotion recognition system can be tested in 2 ways: 
(i) By running a previously uploaded videos. 
![Screenshot](static/camera_access.PNG)

(ii) The user can also give camera access to the application to check the real time model performance.
![Screenshot](static/video_access'.PNG)

STEPS TO RUN THE MODEL ON LOCAL COMPUTER
1. Clone the repository using the following command, in a specific location.
  >git clone https://github.com/leena-bhooshan/Emotion-Recognition

2. Open CMD or Git Bash and navigate to that directory.
  >cd PATH_TO_DIRECTORY

3. Now create a virtual enviroment in which we will run our application. By doing this we can run our application in isolation.
  >python virtualenv venv

4. Activate the virtual enviroment
  >env\Scripts\activate

5. Install Flask using pip in virtual enviroment
  >pip install flask

6. Now we have to set the 'flask app' for flask to run our application. Here 'main' is the file from which the execution will start.
  >set FLASK_APP=main

7. (OPTIONAL) Not we have to set the mode for flask application (development/production) to run. By default the flask app run in production mode. To set the flask app in development mode we have to run the following command.
  >set FLASK_ENV=development

8. Now, the last step which executes the application on locahost using flask.
  >flask run

  ENJOY THE APPLICATION!!!    
  FEEL FREE TO CONTRIBUTE TO THIS APPLICATION . . .

  
 
