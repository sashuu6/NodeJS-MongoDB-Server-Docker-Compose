FROM node:12
LABEL createdby="Sashwat K <sashwat0001@gmail.com>"
LABEL maintainer="Tech With Us <dev@techwithus.com>"

# Update container
RUN apt-get update -y

# Upgrade container
RUN apt-get upgrade -y

# Install nano and git
RUN apt-get install nano git -y

# Clone nodeJS code
RUN git clone --depth 1 https://github.com/dev-techwithus/sample-nodejs.git /usr/share/nodejs
RUN npm install --prefix /usr/share/nodejs
