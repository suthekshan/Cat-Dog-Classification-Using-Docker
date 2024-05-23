# Cat-Dog-Classification-Using-Docker
Image-Classification -Flask-Docker
This project demonstrates a simple web application that predicts whether an uploaded image contains a cat or not. It uses a pretrained machine learning model (h5 format). It is deployed using Flask and containerized using docker.

#Docker Deployment
Build the Docker image: docker image build -t flask_docker .

Run the Docker container: docker run -p 5000:5000 -d flask_docker

Access the app at http://127.0.0.1:5000/upload

#Usage
Upload an image using the web form.

The app will predict whether the image contains a cat or not.

#Demo Video
