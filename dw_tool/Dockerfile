# Container for DW tools
FROM ubuntu:14.04
MAINTAINER Dustin Tran <nhduy1985@gmail.com>
RUN apt-get update && apt-get install -y curl git
RUN curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash - && apt-get install -y nodejs
RUN npm install -g grunt grunt-cli gulp
