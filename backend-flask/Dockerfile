FROM python:3.10-slim-buster


# Event inside of the container
# creates a new folder inside the container
WORKDIR /backend-flask

# Event outside the container
# This file containes libraries to be installed to run the app
COPY requirements.txt requirements.txt


# Event inside the Container
# Install the python libraries required to run the app
RUN pip3 install -r requirements.txt

# Event outside the container
# . means everything inside the current directory
# the first period, . - /backend-flask (outside the container)
# the first period, . /backend-flask (inside the container)
COPY . .


# This sets the environment variables
# Inside container and it will remain set when the container is running
ENV FLASK_ENV=development

EXPOSE ${PORT}

# python3 -m flask run --host=0.0.0.0 --port=4567
# short form of running flask module
# goto unlock the port
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]