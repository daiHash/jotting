# Specified a base image to use
FROM node:14-alpine

# Create app directory
# WORKDIR /usr/src/app
WORKDIR /app

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
# COPY package.json ./
# COPY yarn.lock ./

RUN apk update && \ yarn global add @vue/cli

ENV HOST 0.0.0.0
EXPOSE 8080

# # Default command
# CMD ["yarn", "serve"]