# MangaShareQuickDeployment

MangaShareQuickDeployment is Docker Compose project.
It is composed of 3 containers :
 - Maven
 - Tomcat
 - MySql

## Maven
The Maven container has a sepecific role.
Downlods the project from GitHub, compiles it and puts the .war in a shared volume.

## Tomcat
The Tomcat container gets the .war from the shared volume and deploys it.

## Mysql
Runs with Tomcat container.

# Goal
This project might be forked in the future to others Java-sping-JPA projects.

