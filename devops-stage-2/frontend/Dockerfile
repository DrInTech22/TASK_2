# Use an official Node.js runtime as a parent image
FROM node:20.15.0-alpine

# Set the working directory in the container
WORKDIR /app

# copy the rest of the application code

COPY . /app

RUN npm install

EXPOSE 5173

CMD [ "npm", "run", "dev", "--", "--host" ]

