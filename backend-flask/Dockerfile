FROM 250487559860.dkr.ecr.us-east-2.amazonaws.com/cruddur-python:3.10-slim-buster

# Inside Container
# make a new folder inside the container
WORKDIR /backend-flask

# Outside Container -> Inside Container
# this contains all the libraries we want to install to run our app
COPY requirements.txt requirements.txt

# Inside Container
# Install all the libraries to run the app
RUN pip3 install -r requirements.txt

COPY . .

ENV FLASK_DEBUG=1

EXPOSE ${PORT}
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]