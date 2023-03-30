# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Solution :

Github link : https://github.com/ruchiagarwal26/Ruchiz-ecom-backend

Video Link : https://drive.google.com/file/d/1XQ83ypvWsI-b_IOOaqSOYoXiCtgjCrsP/view

Insomnia scrrenshot:

Images to show the POST, PUT, and DELETE routes for products and tags being tested in Insomnia.

In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products."
![image](https://user-images.githubusercontent.com/115508901/228685170-8feb7f97-b5a6-402a-bdeb-2b03683cf8fe.png)

In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”
![image](https://user-images.githubusercontent.com/115508901/228685242-d2376e48-62ab-4b4a-b7a1-cafe01c875ac.png)

In Insomnia, the user tests “CREATE Category,” 
![image](https://user-images.githubusercontent.com/115508901/228685295-af886158-69a2-4931-a2ae-41c389838a93.png)

In Insomnia, the user tests “UPDATE Category.”
![image](https://user-images.githubusercontent.com/115508901/228685343-87d00d75-7bef-4091-b3f2-98a518e01ed9.png)

In Insomnia, the user tests “DELETE Category by ID"
![image](https://user-images.githubusercontent.com/115508901/228685406-3b73be4d-f469-41e1-9de4-c29934578af1.png)


## Functionalities

With the help of Express.js API and sequilize libraries, the user can:
> Insert initial data in tables that are defined at MySql server
> The connection information is restricted in .env files with no access to other users
> The API is set up for each table
> The user can run below operations:
>    GET : to view all content in tables : Product, Category and Tags
>    GET : view contents of above tables based on id
>    POST : create new content in above tables
>    PUT : Update data in above tables
>    DELETE : delete data based on id from the above tables
> All routes are displayed in the code
> The foreign and primary keys and table constraints are set up to avoid any bad commands


