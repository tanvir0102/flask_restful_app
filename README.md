# flask_restful_app

# Clone the code and change the directory
git clone https://github.com/tanvir0102/flask_restful_app.git
cd flask_restful_app

# build the images of flask app and nginx
docker-compose build

# run it using compose
docker-compose up

# validate the application
http://127.0.0.1:8080/api/v1/user/1

# stop/remove the container
docker-compose up
  
