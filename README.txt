EARTHQUAKE ANALYTICS 

— see the project: http://rio.inf.usi.ch:38090/

how to run:

1. download the repository of Earthquake Analytics
2. enter in the folder and run: mvn install
3. enter in target repository and run: java -jar demo-0.0.1-SNAPSHOT.jar --dbUrl="jdbc:mysql://dbURL/databaseName” --dbUser= “yourDbUser” dbPassword=“yourDbPassword”
4. Spring starts and the code will start to collect informations from INGV earthquake service, fill the database require internet and many hours.
5. goto to http://localhost:8080/ to see the client of earthquake analytics. 
