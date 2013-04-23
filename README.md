Swagger-API-JSON-
=================

Swagger documented JSON of APIs

To install Swagger:
Go to https://github.com/wordnik/swagger-ui and download the Swagger distribution.
Download Apache Tomcat and save in some directory
Store the Swagger-UI folder in apache-tomcat-x.x.x/webapps/docs

To Run Tomcat:
Go into Command Prompt:
cd into Tomcat directory;
cd into /bin;
Run catalina start;
Go to website and type in "http://localhost:8080/docs/Swagger-UI-Master/dist/index.html"

To test JSON file:
copy JSON files into *tomcat*/webapps/docs
Copy "http://localhost:8080/docs/...json" into file link at top

Error codes:
200 ok: Recognizes JSON, but there's syntax error
