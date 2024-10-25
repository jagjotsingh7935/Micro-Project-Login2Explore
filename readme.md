Micro Project Work

contact email : jagjotsingh2287@gmail.com

LINK - https://jagjotsingh7935.github.io/Micro-Project-Login2Explore/

Title of the Project : Student Enrollment Form

Description : Student Enrollment Form that will store data in STUDENT-TABLE relation of SCHOOL-DB database. Input Fields: {Roll-No, Full-Name, Class, Birth-Date, Address, Enrollment-Date}

Primary key: Roll No.

Benefits of using JsonPowerDB : Simplest way to retrieve data in a JSON format. Schema-free, Simple to use, Nimble and In-Memory database. It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX. It is low level (raw) form of data and is also human readable. It helps developers in faster coding, in-turn reduces development cost. Release History (release of your JsonPowerDB related code on Github)

Additional you can have: JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

Table of contents: Roll-No Student Full Name Class Birth-Date Address Enrollment-Date SAVE - INSERT CHANGE - UPDATE DELETE RESET


Scope of functionalities :

Examples of use : can be used foe various other platforms like Online Examination Registration , Job Application , profile creation , and many more other uses .

Project status : Done

Sources :Introduction to JsonPowerDB - V2.0 https://careers.login2explore.com/course/view.php?id=14

Other information Sources : https://login2explore.com/jpdb/docs.html

STEP BY STEP COURSE DOCUMENTATION :

JsonPOwerDB
Introduction to JsonPowerDB - V2.0 Login2Xplore

Creating a Developer Account and Generating Connection Token : -

Visit: http://api.login2explore.com:5577/user/index.html REGISTER After registration check your email-id for password. Login at http://api.login2explore.com:5577/user/index.html using your email and password received. First of all change password - Left Navigation >> Change Password. Login with new password.

Tools > Token > connection token > Generate (Token needed to communicate with Data Base)

90934476|-31949224331436093|90962726

Token used to execute the API

Installing Talend API Tester : -

Google > settings > Extensions > Chrome Web store > Talend API Tester - Free Edition > Add to chrome extension

Understanding JsonPowerDB and its Features : -

nimble , schema Free , simple to use , in memory and real time , easy to maintain , serverless support , enables multi mode database , power Index , Web services API Cost efficient , multiple security layers , best performance

JsonPowerDB Use case and Benefits : -

any software app that needs backend db all rdbms use cases all document db use cases all key- value db use cases use cases that needs GeoSpacial/Time series Analytics Best suited to real - time application for data analytics Improving existing application reporting/ analytics performance. Live working HTML, Templates.

PUT Command - Creating (Inserting) Record : - # IML (JPDB Index Manipulation Language) PUT : Insert single record in the database Token - 90934476|-31949224331436093|90962726

Talend > post Base url : http://api.login2explore.com:5577 End-point url : /api/iml (mentioned in command when different)

BODY : { "token": "90934476|-31949224331436093|90962726 "cmd": "PUT", "dbName": "Employee", "rel": "Emp-Rel", "jsonStr": { "id": "1", "name": "Jagjot", "email": "123a@gmail.com", "mobileno": "996788776" } }

Send >

{"data":"{"rec_no":[1]}","additionalData":{"processReqType":0,"dbUpdateFlag":true}, "message":"RELATION CREATED, TEMPLATE CREATED FROM JSON, DATA INSERTED, Total 1 rows are inserted, Added 0 columns as New Index Columns.","status":200}

Dashboard > Visualize > Jsondb > select Database and Relation

1 26/10/2024, 8:21:16 PM 123@gmail.com 1 996788776 Jagjot

New row -

{ "token": "90932512|-31949274757731994|90949158", "cmd": "PUT", "dbName": "Employee", "rel": "Emp-Rel", "jsonStr": { "id": "2", "name": "ankit", "email": "anki@gmail.com", "mobileno": "8582887792" } }

{"data":"{"rec_no":[2]}","additionalData":{"processReqType":0,"dbUpdateFlag":true}, "message":"DATA INSERTED, Total 1 rows are inserted, Added 0 columns as New Index Columns.","status":200}

Dashboard > Visualize > Jsondb > select Database and Relation

1 25/10/2024, 8:21:16 PM ankia@gmail.com 1 9967825671 ankit 2 , 8:24:57 25/10/2024 PM anki@gmail.com 2 8582887792 ankit



