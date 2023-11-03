# Project README
 Persisting Data Application

The Persisting Data Application can be compiled, launched, and used according to the instructions in this README. The application created in Part 1 is expanded upon in this one, which includes functionality for user registration and login as well as data persistence.

 Contents Table

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Compiling the Application](#compiling-the-application)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
  - [User Registration](#user-registration)
  - [User Login](#user-login)
  - [Working with Data](#working-with-data)
- [Database Setup](#database-setup)
- [Class Diagram](#class-diagram)
- [Change Log](#change-log)

Introduction

An expanded version of the application created in Part 1 is called the Persisting Data Application. This section allows users to securely access their own data by registering with a username and password. Data is stored in a SQL database.

Requirements

Make sure you have fulfilled the following prerequisites before starting:

One appropriate C# development environment is Visual Studio.
- [] SQL Server or a related database technology.

Getting Started

To compile, launch, and utilize the application, follow these instructions.

Compiling the application

1. Launch the `PersistingDataApplication.sln} solution file in the development environment of your choice.

2. Assemble the application by building the solution.

Running of Application 

1. Verify that the database is configured (for instructions, see [Database Setup](#database-setup).

2. Launch the software.

Usage

The program has functions for managing data, logging in, and registering users.

Sign-up of Users

- Click the "Register" button to add a new user.
. Enter your username and password here.
. The password hash is the only thing the software keeps in the database.

#### Login User

- Type in the password and username you registered with.
- Press "Login" to have access to your information.

User Login

You can manage your info as needed once you're logged in. The program makes sure that the only data you can see is your own, and not any other user's.

Database Setup 

For database access, you can use Entity Framework Core or ADO.NET. You might have to create the database and tables by hand, depending on your decision.

Use the Entity Framework CLI to apply database migrations if you're using Entity Framework Core. To create tables when using ADO.NET, you might need to execute a SQL script.

See the data access layer and application source code for details on database configuration unique to your selected technology.

Class Diagram

A summary of the classes used in the class library and application can be seen by viewing the [UML class diagram](uml_class_diagram.pdf). It shows the modifications done to the class library to add the new feature.

Change Log 

View the [ChangeLog.md](ChangeLog.md) file for a comprehensive list of modifications made in response to Part 1 comments.
