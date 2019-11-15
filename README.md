# PUC Minas - test_docker
a simple test to create a docker image for the postgraduate 

# Comands to create and start the image.

docker build -t webserver-image:v1 .
docker run -d -p 80:80 webserver-image:v1

# Testing
just navigate to localhost in a web browser
