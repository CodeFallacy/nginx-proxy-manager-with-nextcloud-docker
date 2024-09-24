# To build run the command where the dockerfile is located: docker build -t my-nextcloud .

FROM nextcloud:latest

# Update package lists
RUN apt-get update

# Upgrade package lists
RUN apt-get upgrade -y

# Install ffmpeg
RUN apt-get install -y ffmpeg

# Install nano
RUN apt-get install -y nano

#Install Node & NPM
RUN apt-get install -y nodejs npm
