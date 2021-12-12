# Create new MySQL Service using Aiven

## Getting started

1. Click on the “Create new service” button on the top right as shown in the picture below. 

![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145692555-860b0b74-366e-4cca-8b0a-b2a48f904014.png
 "createMysqlService1")  

2. Select Your Service from the list of [Aiven Service](https://help.aiven.io/en/collections/341138-services) by clicking on the “MySQL” option as shown in the picture below.


![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145692556-465295e4-7df1-47b3-a901-7367ab1df69d.png
 "createMysqlService2")  

3. Then select the suitable Service [Cloud Provider](https://help.aiven.io/en/collections/341176-clouds-and-regions) , [Service Cloud Region](https://help.aiven.io/en/collections/341176-clouds-and-regions), [Service Plan](), and [Disk Space](). Then give your service a name. In the example we will be creating we will use the default suggestions, except the service plan, we will choose the "Hobbyist" plan.

4. Click on the "Create" button

Now, you will be redirected to your current services page, where you will find your list of Databases, including the one we just created!

The new Database will start building, and when it is ready it will show its status as "Running" in green as shown in the picture below. 

Very easy!
![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145693482-7ec0db0a-909f-44b6-bec1-9467d3d82a3e.png  "createMysqlService3")  
 
 ## Connect the new service to your local database design tool
 
Well, now we need to connect our database to the tool that we will be using to design it. There are many tools that we can use, in this example we'll be using MySQL Workbench.

If you would like to install MySQL Workbench, please click [here](https://dev.mysql.com/downloads/) and follow the installation steps!

1. We first need to define the parameters by setting up a new connection, by clicking on the plus sign as shown in the picture below.

![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145695025-bd72a030-061f-4aa9-9ccd-85539e624410.png
 "createMysqlService4") 

2. Go to your database service on Aiven and copy the corresponding parameters' values into Workbench, and give a name to your Connection as shown in the pictures

![Stormtroopocat]("https://user-images.githubusercontent.com/6803398/145695026-72302587-9426-4a9a-a9be-e76f0c054880.png
 "createMysqlService5") 
![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145695032-92bc160c-b54a-4815-825c-0e46ec43edc4.png
 "createMysqlService8") 

3. Download the "CA Certificate" and attach it to the "SSL CA File" under the SSL section in Workbench as in the picture below


![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145695031-7d81ee60-4a72-4e25-b325-d25d8dced061.png
 "createMysqlService7") 

4. Test your Database connection by clicking on the "Test Connection" button

5. When the connection is successful as in the picture shown below, click the "Ok" button

![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145695034-eb127391-f8dd-4802-b474-8b250a277e46.png
 "createMysqlService9") 

Now you are ready to start the fun part! :sunglasses:

## Create Database Tables

1. Now, we will test our Database by creating a small example of 2 tables, adding some records, and then observe our Aiven application!

2. In this example, we will create a "Persons" table and "Cats" table from Workbench, as shown in the picture.
![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145720605-172fd0ad-52d3-46b6-b3e2-caee79f98133.png
    "createMysqlService110") 
3. Then we created 1 instance of Persons and 2 instances of cats

![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145720608-951742f8-cc06-47d5-8376-5a9d4540cc0f.png
    "createMysqlService111") 

4. Next, you can check your Aiven service, you will find different views that show information about your database, for example, you can check the logs and the Query statistics as shown below
![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145721257-dab66c9f-aeb6-4923-9078-141eaf3597d7.png
    "createMysqlService12") 
![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145720609-239ac246-eca9-420f-8bab-db4e0debdf60.png
    "createMysqlService13") 
![Stormtroopocat](https://user-images.githubusercontent.com/6803398/145720611-ed2a5dbc-5c75-4beb-a9b2-e0c5a18260cc.png
    "createMysqlService14") 


Now, you are ready to work with MyDQL on the Aiven platform!









