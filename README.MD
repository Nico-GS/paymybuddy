<h1>PayMyBuddy App - Send Money</h1>

<p><b>PayMyBuddy</b> is an application for sending money to friend's account</p>

<h3>Model Database (SQL)</h3>

![Model BDD](https://github.com/Nico-GS/PayMyBuddy/blob/master/SQL/ModeleBDDImg.png)

<h3>UML Diagram</h3>

![Diagram UML](https://github.com/Nico-GS/PayMyBuddy/blob/master/SQL/UMLClasse.png)

<h3>The SQL Script</h3>

Contains the principal database and the database for the tests

https://github.com/Nico-GS/PayMyBuddy/blob/master/SQL/script.sql

<h3>Required</h3>

Java 14
<br><br>
Spring Boot 2.3.4
<br><br>
Maven 4.0.0
<br><br>
MariaDB (or MySQL) 10.5.8
<br><br>
Jasypt 1.9.3 : http://www.jasypt.org/download.html For encrypt the database password
<br>
<b>./encrypt.sh input=passwordToEncrypt password=KeyPassword</b>
<br><br>
jBCrypt for encrypt user password in database : https://www.mindrot.org/projects/jBCrypt/


