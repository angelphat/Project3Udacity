# Use NodeJS base image
# FROM node:13

## Build
FROM nginx:alpine
COPY nginx.conf /etc/nginx/nginx.conf
# Create app directory
# WORKDIR /usr/src/app
# Install app dependenciesdoc
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# COPY package*.json ./
# RUN npm ci
# # Bundle app source
# COPY . .
# RUN ionic build
# ## Run 
# FROM nginx:alpine
# #COPY www /usr/share/nginx/html
# COPY --from=ionic  /usr/src/app/www /usr/share/nginx/html