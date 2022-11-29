# FlaskML
Flask + ML predictor Positive or Negative Feedbacks


Feedbacks classification: Positive - 100% or Negative - 0%

#Instructions:

#Install requirements.txt
-- pip install -r requirements.txt

#Build docker container from app directory FlaskML 
-- docker build -t app .

#Start docker
-- docker run -p 8180:8180 -p 8181:8181 -v /your path/FlaskML/app/models:/app/models app

#Check frontend on http://127.0.0.1:8181
#Fill predict form and get predictions
