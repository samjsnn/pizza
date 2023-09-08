# Use Node Version 18
FROM node:18

RUN mkdir -p /usr/src/app

# Copy Project Dependencies List from to the working directory
COPY package*.json /usr/src/app

WORKDIR /usr/src/app

# Install Project Dependencies
RUN npm install

# Copy Source Code Over
COPY . /usr/src/app

# Expose Ports
EXPOSE 8080

# Run Node Server
CMD ["node", "server.js"]
