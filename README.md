# Dokerized Rest API using React.js and MongoDB

In this application, an initial state has been set to develop a Rest API using React.js and MangoDB, all included in Docker containers. 

This repository therefore allows you to have a working API to start developing an ecommerce or any other API application.

- The first step to get started is to create the .env file:

      cp .env.sample .env

- Then use the following command to start the application:

      docker compose up -d

- To check that the application is working, go to the following website

      http://0.0.0.0:${NODE_LOCAL_PORT}/api/test

      NODE_LOCAL_PORT -> is inside the .env file.


The application updates the code inside the container in real time, allowing you to have a development environment that updates React every time the code changes.

Have fun with this new tool! =)
