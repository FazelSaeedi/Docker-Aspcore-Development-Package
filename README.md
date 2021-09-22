# Docker-Aspcore-Development-Package
a package for publishing asp core applications on Docker-Nginx


Instruction to run -------------------------------------------------------------------------------


    1. First of all you should install docker 

    2. go to each application and excute 
        2.1. dotnet build 
        3.2. dotnet publish -c release

    3. in root of project execute docker-compose up


    4. you can see projects -> 
        http://localhost:8084/app1
        http://localhost:8084/app2

    5. Now have a container includes 2 Asp.net Core 5 application & Nginx for routing them     
    
    
Feature work -----------------------------------------------------------------------------------


    1. Containerize MSSQL ,  Redis & MONGO database 

    2. Containerize elastic search 

    3. Containerize RabbitMq message broker

    4. Containerize Gitlab and finally CL/CD


-------------------------------------------------------------------------------------------------


