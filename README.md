# internship-bim-project
### app created with Java

### Table of contents
* General info
* Technologies
* Setup
* Sources
* Bugs

### General info
App was created to convert <b>ifc</b> file to <b>json</b> 
and database support. This app it is designed with
the industry in mind. 

### Technologies
Project was created with: 

* Java Development Kit (JDK) corretto 16.0.2
* org.json Library 20220320

### Setup
* Open commandline and cd to folder wherein app is loacted
* Write `javac dataOperations.java && java dataOperations` in commandline

### Sources
* https://www.oracle.com/technical-resources/articles/java/json.html
* https://docs.oracle.com/javase/7/docs/api/javax/xml/parsers/DocumentBuilder.html
* https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/xmldoc/
* https://www.ibm.com/docs/en/db2/11.5?topic=concepts-json-documents

### Bugs
There are some bugs in the app. 
The application converts and saves data to a .json file, 
but the fields: Layer, id (Property Set), name (Property Set), 
name (Properties) and value (Properties) are written in the 
wrong places.