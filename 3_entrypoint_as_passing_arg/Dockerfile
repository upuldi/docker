# When you use an entry point in the docker file all the commands you pass to the container becomes arguments to 
# the entry point command, this is different to using CMD as when you are using CMD you can override the command
# defined by the CMD
FROM ubuntu
MAINTAINER upuldi@gmail.com
RUN apt-get update && apt-get install iputils-ping  --assume-yes 
ENTRYPOINT ["ping"]
