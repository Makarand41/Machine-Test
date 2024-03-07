# Django Machine Test

## Users

1] admin       password: admin

2] Rohit       password: admin

3] Ganesh      password: admin

## Endpoints

1] List of all clients : 

GET:    http://127.0.0.1:8000/clients/

2] Create a new client :

POST : http://127.0.0.1:8000/clients/

3] 
Retrieve info of a client along with projects assigned to its 
users : 

GET : http://127.0.0.1:8000/clients/id/

eg] http://127.0.0.1:8000/clients/4/

4] Update info of a client

Put : http://127.0.0.1:8000/clients/id/

5] Delete a client

Delete : http://127.0.0.1:8000/clients/id/

6] Create a new project

Post :  http://127.0.0.1:8000/clients/:id/projects/

7] List of all projects assigned to the logged-in user

GET : http://127.0.0.1:8000/projects/


## Note for all

when creating a project , it first takes 2 parametes 1. created by and 2. client , now *submit it* and then it will redirect to create the project .Here you can submit the project.


## Screenshots


1]  List of all the clients
![image](https://github.com/Makarand41/Machine-Test/assets/90332486/ffa5130c-f1a9-46d3-88a6-6bcd183e323e)

2] Add a client
![image](https://github.com/Makarand41/Machine-Test/assets/90332486/7b7c9886-e512-4d99-8b75-8f838c9f25df)

3] Update a clinet
![image](https://github.com/Makarand41/Machine-Test/assets/90332486/6ef3b0cb-02e8-4ea4-a5ca-948d44b8a613)

4] Delete a client
![image](https://github.com/Makarand41/Machine-Test/assets/90332486/903bee05-632d-4da1-8595-ba76a064dda7)

5] GET /clients/:id  

![image](https://github.com/Makarand41/Machine-Test/assets/90332486/ba5341fc-f280-4ada-aed8-e342686e1b62)

6] Add project

![image](https://github.com/Makarand41/Machine-Test/assets/90332486/f00731bf-64c8-49fd-acbe-f7bfd6ce389e)
After that it will be redirected to 
![image](https://github.com/Makarand41/Machine-Test/assets/90332486/d2a081db-2c14-475a-8dc4-c58848c79554)


7] List of all projects

![image](https://github.com/Makarand41/Machine-Test/assets/90332486/379e113f-5d3e-4429-a6ac-22d1436a4498)
