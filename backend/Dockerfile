# Get the base node image
FROM node:16-alpine 

# Author: Moringa School
LABEL maintainer="Moringa School <moringaschool.com>"

# Set the working directory to /frontend
WORKDIR /backend

# Copy all files to the working directory
COPY ./ /backend

# Install dependencies
RUN npm install

EXPOSE 5050

# Start the application
CMD npm start