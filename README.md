# springbootsetup



Spring boot set up using JAVA 17:
Step 1- Open Spring boot app or any IDE like eclipse, intelligec, etc
Step  2- Click on file menu and then new project.
Step 3- Install java 17 on your local machine and set the path using environment.
Step 4- In pom.xml, make sure java version is showing java 17 and then install the projects.
Step 5- For database configurations, open application.properties file in src/main/resources directory and set up the database authentications. For example-
spring.datasource.url=jdbc:mysql://127.0.0.1:3306/dbname?useSSL=false&serverTimezone=UTC&useLegacyDatetimeCode=false
spring.datasource.username=root
spring.datasource.password=root
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5Dialect
spring.jpa.hibernate.ddl-auto=update
logging.level.org.hibernate.SQL=DEBUG

Step 6- Go to the directory of the project, open command prompt there and type 
o	mvn clean install
Step 7- If you change pom.xml then repeat step 6 again and again.
Step 8- Then create MVC model in the project by creating packages.
Step 9- Run Spring boot application, then create rest api and spring profiles.
