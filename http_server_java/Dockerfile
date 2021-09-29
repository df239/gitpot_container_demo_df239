FROM java:alpine

WORKDIR /app/

RUN apk add --no-cache subversion && true
RUN svn export https://github.com/calaldees/javalib/trunk/lib/Utils/Utils

RUN javac Utils/Apps/WebServer.java

RUN find ./ -iname *.java -delete

ENTRYPOINT ["java","Utils.Apps.WebServer"]
CMD ["./"]