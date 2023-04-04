# CRUD-Application

This is a basic CRUD Application to add,edit,view,search and delete customer details.
## Tech Stack involved:
- HTML
- CSS
- NodeJS
- ExpressJS
- Database : MongoDB

## Guide to creating MongoDB Database and .env File
- Create a free MongoDB Atlas account and create a .env file in the project folder as well
- Create a new project and enter the following:
    - Name
    - Owner and permissions 
    - Add current IP Address to add the Database to your IP Address
- Build a database and choose the free M0 version and choose the following:
    - Region
    - Provider
    - Cluster Name
    - Username
    - Password (Autogenerate)
- Copy the above username and password and paste in the .env file
- Connect using VS Code to your MongoDB Deployment with the string given
- Example below:

```
MONGODB_URI = mongodb+srv://<username>:<password>@mongodburlhere
```
## Demo
https://user-images.githubusercontent.com/63198668/229792114-b6ad1126-af6f-4edb-b134-c5ad9983fa47.mp4



## Installation
To install and run this project - install dependencies using npm and then start your server:

```
$ npm install
$ npm start
```

