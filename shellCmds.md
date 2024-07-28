![image](https://github.com/user-attachments/assets/b3831621-9765-4d68-9c27-b615f18cb3b8)

## To get started with MongoDB and create databases in it, we need to perform the following steps:

1) Create MongoDB Cluster
2) Install MongoDB Shell
3) Connect to MongoDB

##  Creating a MongoDB cluster involves:

### 1) Creating MongoDB account
In the first step select Username and Password
Enter your Username in the Username field.
Enter the Password in the Password field.
In the second step select My Local Environment.
Enter 0.0.0.0 in the IP Address field

### 2)  Creating Cluster
once u have created account in mongodb ,
1) set username
 2) set password
3) set ip address to 0.0.0.0
4) click enter and finish
5) now the cluster is created 

## steps  
1) download the mongo shell and extract the files in a folder 
2) open the terminal and type mongosh --version
3) if the above command runs without error , it shows that the mongodb shell  is successfully installed

## Connect to the Database using Shell
 1) Get the connection string of the cluster  from the website and execute it in the terminal

2)Enter the user password and press the enter key.
3)In order to get the available databases, we can use the show dbs command.



# commands 
### To  Create a Database 
use <databaseName>
### To create a collection, 
we use createCollection()
### Retrieve all the collections from the database.
we use db.getCollectionNames()
