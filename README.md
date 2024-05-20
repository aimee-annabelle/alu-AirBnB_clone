# alu-AirBnB_clone

###Project description
In this project, we will replicate the console component of the AirBnB clone project.

Our task involves developing a command interpreter to manage various AirBnB objects.

Key steps include:

1. Establishing a parent class, called BaseModel, to handle the initialization, serialization, and deserialization of future instances.
2. Implementing a straightforward serialization/deserialization workflow: Instance < - > Dictionary < - > JSON string < - > File.
3. Creating all classes used for AirBnB (such as User, State, City, Place, etc.) that inherit from BaseModel.
4. Developing the initial storage engine for the project: file storage.
5. Writing unittests to validate all classes and the storage engine.

Our command interpreter would be able to:

```bash
Create a new instance (e.g., a new User or a new Place).

Retrieve an instance from a file, database, etc.

Perform operations on instances (count, compute statistics, etc.).

Update the attributes of an instance.

Delete an instance.
```
