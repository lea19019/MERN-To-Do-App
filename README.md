# ToDo App Overview

ToDo App implementation using a MongoDB database stored in the cloud. This project is meant to help me practice and demonstrate the usage of a cloud database such as MongoDB. The project performs CRUD operations and is build on a Node.js environment and uses a simple frontend app to consume the REST API to display the data.

The functionality is still under development, but you will be able to add a task, remove a task, edit a task, mark completed or active task. The app will also allow you to have your own user, the user will have the register, login and logout functionalities, and depending on who is the user it will display its tasks.

[ToDo App Demo Video](https://youtu.be/zbn0XOh1DtU)

# Cloud Database

As mentioned above MongoDB is the cloud databased selected for this project.

The data is stored in a todoApp table, which contains only one collection named todoList.
The todoList collection contains our objects, and these objects have the followind structure:
* _id: ObjectId
* taskId: string
* content: string
* isCompleted: bool

It is currently perfoming CRUD operations by creating complete objects, reading all objects or the completed or the not completed. It also has the capability to update a task, and delete tasks.
Some of the functions of MongoDB include insertOne, find, updateOne, deleteOne, with different types of queries to filter the data.  

# Development Environment

* MongoDB 4.4.6
* Node.js 14.16.1
* Visual Studio Code

## Libaries
* body-parser 1.19.0
* express 4.17.1
* mongodb 3.6.9
* nodemon2.0.7
* path 0.12.7

# Useful Websites

* [MongoDB Homepage](https://www.mongodb.com/)
* [MongoDB Documentation](https://docs.mongodb.com/)
* [Node.js Documentation](https://nodejs.org/en/docs/)

# Future Work

## MongoDB & Backend
* Create User collection
* Implement user creation
* Authentication proccess

## Frontend
* Display completed and pending dinamically
* Delete and Update task
* Fix redirection when adding task