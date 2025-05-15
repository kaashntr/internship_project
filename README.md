[# Class chedule
## General info
This repository contains a source code of the Class Schedule Project.

The main goal of the project is designing a website where the university or institute staff will be able to create, store and display their training schedules.

Link to the development version of the site: https://develop-softserve.herokuapp.com/

## Dockerless

## Creating a local repository
In order to create a local copy of the project you need:
1. Download and install the last version of Git https://git-scm.com/downloads
2. Open a terminal and go to the directory where you want to clone the files. 
3. Run the following command. Git automatically creates a folder with the repository name and downloads the files there.

       git clone https://github.com/kaashntr/internship_project.git

## Database
1. Download and install the last version of PostgreSQL https://www.postgresql.org/download/
2. Configure your username, password and connection url in `src/main/resources/hibernate.properties` file
3. Create USER in db with:

       CREATE USER tomcat WITH PASSWORD 'your_password_here';

4. Create DATABASE for user with:

       CREATE DATABASE schedule OWNER tomcat;

5. Grant All Privileges with:

       GRANT ALL PRIVILEGES ON DATABASE schedule TO tomcat;
       GRANT ALL PRIVILEGES ON ALL TABLES IN SCHEMA public TO tomcat;


## Redis
1. Download and install the last version of Redis  https://redis.io/download
2. Configure connection url in `src/main/resources/cache.properties` file

## MongoDB
1. Download and install last version of MongoDB https://www.mongodb.com/docs/manual/administration/install-on-linux/
2. Configure connection url in `src/main/resources/mongo.properties` file


## Starting frontend server using Node.js
1. Download and install Node.js 14.17.4 LTS version https://nodejs.org/en/
2. Open a terminal in `/frontend` directory of the downloaded project and run the following command.
3. 

       npm install
4. After the installation is finished run the following command to start the frontend server

       npm start](https://github.com/kaashntr/internship_project)
