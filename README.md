AirBnB clone - The console 🏠🏠 

![alt text](image-1.png)

PROJECT DESCRIPTION 

Here, We'll be cloning the console part of the AirBnB clone Project.

We'll be writing a command interpreter to manage our AirBnb objects.

We'll need to

1. put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of our future instances

2. create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file

3. create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel

4. create the first abstracted storage engine of the project: File storage.

5. create all unittests to validate all our classes and storage engine


What’s a command interpreter?

Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

. Create a new object (ex: a new User or a new Place)
. Retrieve an object from a file, a database etc…
. Do operations on objects (count, compute stats, etc…)
. Update attributes of an object
. Destroy an object
