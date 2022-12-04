# Get the base node image
FROM node:16-alpine 

# Author: Moringa School
LABEL maintainer="Moringa School <moringaschool.com>"

# Set the working directory to /frontend
WORKDIR /frontend

# Copy all files to the working directory
COPY ./ /frontend

# Install dependencies
RUN npm install

# Start the application
CMD npm start
