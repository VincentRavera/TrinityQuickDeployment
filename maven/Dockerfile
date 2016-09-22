FROM maven:3.2-jdk-7-onbuild

MAINTAINER Vincent RAVERA <ravera.vincent@gmail.com>


RUN git clone https://github.com/VincentRavera/MangaShare /home/root/Application


WORKDIR /home/root/Application

RUN mvn clean install

RUN cp target/*.war /volume/

