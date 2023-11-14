# Server-Client-library
This project is a comprehensive library system that allows users to perform CRUD operations—Create, Read, Update, and Delete—on a library database. It is built on Derby, JavaFX, and SQL, enabling efficient management of library resources and data. The system features a server-client architecture with a main client and a server component, facilitating smooth interaction with the database.

PREREQUISITES

To run this application, ensure the following prerequisites are met:
- Derby: Install Derby, a relational database management system, to handle the storage of library data.
- IntelliJ IDEA (IJ): The project is designed to work with IntelliJ IDEA. Ensure you have it installed to easily manage and run the code.
- JavaFX Configuration: Set up the PATH for JavaFX to ensure the graphical elements work, make sure to add the .controls and .fxml modules.

DATABASE CONFIGURATION

Derby Setup: Follow these steps to create and configure the database using IntelliJ IDEA.
- Open IntelliJ IDEA and locate the Database Tool Window.
- Connect to Derby by specifying the necessary parameters (username, password, database URL).
- Execute SQL scripts or commands to create the necessary tables and schema for the library system.

CREATING THE DATABASE

In console 1 cd into the folder of the project and then drag the IJ.exe on the console to execute it
- Run this command to create the database files:
    connect 'jdbc:derby:books;create=true;';
- Run this command to run the database:
    run 'books.sql';

COMPILING THE APPLICATION

- In console 2 cd into the project and run the necessary code to compile with javaFX, for example:
javac --module-path [your-path-to-javaFX-sdk-lib] --add-modules javafx.controls,javafx.fxml *.java

RUNNING THE APPLICATION

Starting the Server:
In console 3 cd into the project and run the necessary code to run the server with javaFX, for example:
- java --module-path your-path-to-javaFX-sdk-lib] --add-modules javafx.controls,javafx.fxml server

Starting the Client:
In console 4 cd into the project and run the necessary code to run the server with javaFX, for example:
- java --module-path your-path-to-javaFX-sdk-lib] --add-modules javafx.controls,javafx.fxml cliente

Performing CRUD Operations:
With the application running, you can access the functionality to register, add, delete, modify, and search by various parameters in the library system.

Data Export Functions:
Utilize the available functions to download library data in formats such as XML, JavaScript, and CSV.

CONTRIBUTION AND ISSUES
Feel free to contribute to this project by forking the repository and submitting pull requests. If you encounter any issues or have suggestions, please create a new issue on this repository.
