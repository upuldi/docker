# This is a base image with build triggers to copy files to the root folder
FROM ubuntu
MAINTAINER upuldi@gmail.com
RUN apt-get update && apt-get install nodejs  --assume-yes && apt-get install npm  --assume-yes 
ONBUILD ADD . /
ONBUILD RUN npm install
