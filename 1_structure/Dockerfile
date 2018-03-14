FROM alpine
MAINTAINER upuldi@gmail.com
RUN apk update && apk add nodejs
RUN mkdir testFolder
ADD Test.js testFolder/
WORKDIR testFolder
ENTRYPOINT ["node","Test.js"]
