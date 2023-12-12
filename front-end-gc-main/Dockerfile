# Dockerfile
FROM node:lts

RUN mkdir /home/node/app && chown node:node /home/node/app
RUN mkdir /home/node/app/node_modules && chown node:node /home/node/app/node_modules

WORKDIR /home/node/app
USER node

# Copy only the package files first
COPY --chown=node:node package*.json ./

# Install dependencies
RUN npm install --quiet --force

# Copy the rest of the application
COPY --chown=node:node . .