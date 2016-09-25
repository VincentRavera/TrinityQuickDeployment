FROM maven:latest

MAINTAINER Vincent RAVERA <ravera.vincent@gmail.com>


RUN git clone https://github.com/VincentRavera/MangaShare /usr/src/app
WORKDIR /usr/src/app
RUN mvn clean install
cmd cp target/*.war /mnt/
