#Specifying a base image
FROM node:alpine

WORKDIR /usr/app

#Command to install additional programs
COPY ./package.json ./ 
RUN npm install
COPY ./ ./

#command that should run after the container started
CMD ["npm", "start"]

# Use docker build -t vaibhavarora19/simplewb . to build
# Use docker run -p 8080:8080 vaibhavarora19/simpleweb to start the container