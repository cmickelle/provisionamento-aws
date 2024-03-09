# Use an official Node.js runtime as a parent image
FROM node:14

# Set the working directory inside the container
WORKDIR /app

COPY application/worker .

RUN npm install

CMD ["node", "worker.js"]
