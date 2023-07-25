# Use an official Node.js runtime as the base image
FROM node:17

# Set the working directory in the container
WORKDIR /app

# Copy the package.json and package-lock.json files to the container
COPY package.json .

# Install the required dependencies
RUN npm install

# Copy the remaining files to the container
COPY . .

EXPOSE 1337

# Specify the command to run when the container starts
CMD [ "npm", "start" ]