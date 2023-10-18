# Hotel Management Application

 Basic hotel management application showing persistence functionality using JPA and Hibernate

***

## Framework and Languages
* Java Platform 8
* JDK 20
* Maven
* SpringBoot starter web - ver. 1.3.1

## Data Flow
This section outlines implementation of the Components.
## Room
1. ### Controller
   The REST Controller is implemented in the Controller.java class. It contains definitions for the following API.

   | Type   | Mapping     | Data Input       |
   |--------|-------------|------------------|
   | POST   | /room       | RequestBody Room | 
   | GET    | /getAllUser | -                | 

2. ### Services

* >String addRoom(Room newRoom)

  Adds new Room to the Database to the Database.

* >List<Room> getRooms()

  Returns a list of all rooms with their id.

## Repository
    CrudRepo with basic CRUD functions
## DataBase Design
    H2 Database, single table.
