FROM ubuntu:latest
RUN apt-get update
RUN apt-get -y upgrade
RUN apt install -y  openjdk-17-jdk
RUN java -version
COPY /app /usr/local/cabinet-app
CMD ["bash", "/usr/local/cabinet-app/start.sh"]
