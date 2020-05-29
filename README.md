# SpringBoot-H2-CRUD-Operation
Spring Boot with H2 Database - CRUD Operation

Somehow, the newer version of H2 Database seems to have issues, which can be resolved by some configuration changes, which is unnecessary if you are using version 1.4.197.
But the link to download this version has been removed from their official website.
So, you may download the same from Maven Central using this link:

https://repo1.maven.org/maven2/com/h2database/h2/1.4.197/h2-1.4.197.jar

Mockaroo lets you generate up to 1,000 rows of realistic test data in CSV, JSON, SQL, and Excel formats.

https://mockaroo.com/

Table-Import-Script-Into-H2-Database:<br/>
To import the existing table (tbl_customer) in H2 Database:<br/>

<b>runscript from '/E:/SpringBoot/Table/tbl_customer.sql'</b><br/>

![Table-Import-Script-H2-Database](https://user-images.githubusercontent.com/35772312/83239416-760df480-a1b5-11ea-8a05-2423e6676378.png)

<b>Swagger API Documentation:</b><br/>

![Swagger-API-Documentation](https://user-images.githubusercontent.com/35772312/83240231-ba4dc480-a1b6-11ea-8406-f7c7ac98a42c.png)

![API_Documentation](https://user-images.githubusercontent.com/35772312/83240813-8b841e00-a1b7-11ea-9a3e-7bea16a3bf2d.png)

<b>To Create a Distributable Jar File:- (Right click on the Project -> Run As -> Maven install)</b>

![2020-05-29 14_41_44-Photos](https://user-images.githubusercontent.com/35772312/83243567-b7090780-a1bb-11ea-82ce-a19242de6d71.png)

Jar file will get created under "target" folder with the name :- <b>springboot-crud-demo-0.0.1-SNAPSHOT.jar</b>

![2020-05-29 14_52_04-](https://user-images.githubusercontent.com/35772312/83244220-a6a55c80-a1bc-11ea-9d7b-d2432dcefa65.png)

To run the Jar File, below is the following command:<br/>

![2020-05-29 15_02_24-C__Windows_System32_cmd exe](https://user-images.githubusercontent.com/35772312/83244987-c426f600-a1bd-11ea-9c38-ea52317d7766.png)

To override any property from the "application.properties" file, and then run the Jar File, below is the following command:<br/>

