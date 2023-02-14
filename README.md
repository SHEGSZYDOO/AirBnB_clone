0 -Write a README.md:

        ◦ description of the project

        ◦ description of the command interpreter:

            ▪ how to start it

            ▪ how to use it

            ▪ examples

    • You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository. For format, reference Docker’s AUTHORS page

    • You should use branches and pull requests on GitHub - it will help you as team to organize your work

1 - Write beautiful code that passes the pycodestyle checks. 

2 - All your files, classes, functions must be tested with unit tests 

3 - Write a class BaseModel that defines all common attributes/methods for other classes: 

4 -  Previously we created a method to generate a dictionary representation of an instance (method to_dict()).

         Now it’s time to re-create an instance with this dictionary representation.

       5 - Now we can recreate a BaseModel from another one by using a dictionary represen tation:

       6 - Write a program called console.py that contains the entry point of the command interpreter: 

       7 - Update your command interpreter (console.py) to have these commands: 

       8 - Write a class User that inherits from BaseModel: 

       9 - Write all those classes that inherit from BaseModel: 

      10 - Update FileStorage to manage correctly serialization and deserialization of all our new         classes: Place, State, City, Amenity and Review

Update your command interpreter (console.py) to allow those actions: show, create, destroy, update and all with all classes created previously.

