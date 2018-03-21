# This is the shell format used with CMD
# this is how to run this image docker run <image_name> -c 3 www.google.com 
FROM ubuntu
MAINTAINER upuldi@gmail.com
RUN apt-get update && apt-get install iputils-ping  --assume-yes 
CMD $PATH ping
