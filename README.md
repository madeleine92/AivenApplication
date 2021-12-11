# Create new MySQL Service usineg Aiven

## Getting started

1. Click on the “Create new service” button on the top right as shown in the picture below. 

![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145692555-860b0b74-366e-4cca-8b0a-b2a48f904014.png
 "createMysqlService1")  

2. Select Your Service from the list of [Aiven Service](https://help.aiven.io/en/collections/341138-services)   when selecting the service by clicking on “MySQL” option as shown in the picture below.


![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145692556-465295e4-7df1-47b3-a901-7367ab1df69d.png
 "createMysqlService2")  

3. Then select the suitable Service [Cloud Provider](https://help.aiven.io/en/collections/341176-clouds-and-regions) , [Service Cloud Region](https://help.aiven.io/en/collections/341176-clouds-and-regions), [Service Plan](), and [Disk Space](). Then give your service a name in step 6. In the example I am creating I will use thr default suggestions, except the service plan, I will choose the "Hobbyist" plan.

4. Click on the "Create" button

Now, you will be redirected to yur "Current services" page, where you will find your list of Databases, including the one we just created!

The new Database will start building and when it is ready it will show its status as "Running" in green as in the picture below. 

Very easy!
![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145693482-7ec0db0a-909f-44b6-bec1-9467d3d82a3e.png  "createMysqlService3")  
 
 ## Connect the new service to your local database design tool
 
Well, now we need to connect our database to the tool that we will be using to design it. There are many tools that we can use, in this example we will be using MySQL Workvench.

If you would like to install MySQL Workbench, please click [here](https://dev.mysql.com/downloads/) and follow the installation steps!

1. We first need to define the parameters by setting up a new connection, by clicking n the plus sign as shown in the picture below.

2. Go to your database service on Aiven and copy the corresponding parameters' values into Workbench

3. Download the "CA Certificate" and attach it to the "SSL CA File" under the SSL section in Workbench as in the picture below

4. Test your Database connection by clicking on the "Test Connection" button

5. when the connection is successful as in the picture shown, click the "Ok" button

Now you are ready to start the fun part!

## Create Database Tables

Now, we will test our Database by creating a small example of 2 tables, adding some records, and observe our Aiven application!

In this example, we will create a "Persons" table and "Cats" table from Workbench.



## Try out your new MySQL service


