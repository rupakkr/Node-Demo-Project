# Tutorial Manager System(Demo) 
Node demo project to manage tutorials, it contains two separate projects.
1. Backed Project - It manages all the APIs needed to manage the tutorial Management system, such as creating a new tutorial, updating a tutorial,
   , getting all the list of created tutorial etc.
2. Front End Project - Its contains UI to view all the tutorials and their detail, along with the supported features such as adding new tutorial, publishing a tutorial
   , deleting a tutorial etc.
   
  
## Back End Project 
### Setup

Update the mongodb connection url in the db-coinf.js file

Go inside the backend project root directory by using below command.
```bash
cd <directory path>
```
Run below command to install the dependencies of the project.
```bash
npm install
```
### Run
run the below command from the present working directory
```bash
node server.js
```
## Front End Project
### Setup
Go inside the front end project directory using below command.
```bash
cd <directory path>
```
Run below command to install all the dependencies of the project.
```bash
npm install
```
### Run
Run the below command form the present workign directory of the project.
```bash
ng server --port 8081
```
## Enjoy
