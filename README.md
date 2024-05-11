# AirBnB clone - The console 🏠🏠
## AirBnB Clone

![alt text](image-1.png)


# PROJECT DESCRIPTION
Welcome to the AirBnB Clone Console! This project aims to replicate the console part of the AirBnB clone project. In this console, we'll be writing a command interpreter to manage our AirBnB objects effectively.

# Objectives

1. BaseModel Class: Implement a parent class called BaseModel responsible for initialization, 

2. serialization, and deserialization of future instances.
Serialization/Deserialization Flow: Establish a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> File.


3. AirBnB Classes: Create all classes used for AirBnB (e.g., User, State, City, Place) that inherit from the BaseModel.

4. Storage Engine: Develop the first abstracted storage engine of the project: File storage.


5. Unit Tests: Write all necessary unit tests to validate all classes and the storage engine.


# What’s a command interpreter?
The command interpreter is a user interface that allows users to interact with the application by entering commands. Similar to a shell, it provides functionalities such as creating new objects, retrieving objects, performing operations on objects, updating attributes, and destroying objects. However, it is tailored specifically for managing objects within our AirBnB project.

# Command List

Here are some of the commands you can expect to use within our console:

create:Create a new object (e.g., User, Place).
show: Retrieve an object from a file, a database, etc.
update: Update attributes of an object.
destroy: Destroy an object.
count: Count the number of objects.
stats: Compute statistics on objects.