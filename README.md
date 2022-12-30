# SGA-JavaEE-WEB
In this project I put in practice skills as JavaEE, EJB, JPA/Hibernate, DAO, JPQL, Api de Criteria, Ajax, JSF, Prime Faces, RESTful Web Services, Web Services and others technologies related to Java
# How to run 
First of all you have to install glassFish server 5.0 in your disk drive closer to the operating sistems in a folder you should create as AppServers. After that you have to configure it, in the route folder C:\AppServers\glassfish5\glassfish\lib you have to download and add in this location the mysql-connector-j-8.0.31.jar that it going to allows you to conect to MySql, after that in ApacheNetbeans add the GlassFish Server version 5.0 or 5.0.1, going to services, servers and then add server, Netbeans is going to guide you througt the process.

After that you have to configurate the String Conection in the domain admin console of glassfish in JDBC Connection Pools add a new New JDBC Connection Pool
with name PersonaPool, resource type = javax.sql.ConectionPoolDataSource, Datasource class name = com.mysql.cj.jdbc.MySqlDataSource and with all options by default and
then click save.

# Database Schema
![sgadb2](https://user-images.githubusercontent.com/94880683/210024192-b31d49f7-51fa-40d5-9cdc-453cf50d9e28.png)

Remember that you should change the user and the password acording with the credentials of your MySql Workbench in the persistence.xml document in the project. In case of having problems to run this project try to search on google the exception that trows you in the glass fish server cosole. I made this project with ApacheNetbeans for this reason all this explanation was made according with this IDE.
 
