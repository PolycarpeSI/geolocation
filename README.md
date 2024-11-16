# patients_geolocation
Project to locate patients in order to facilitate their home appointments by medical specialists

In order to run this app, follow the following steps: 
1- Install mvn if you don't have it (choco install mvn ------> for windows environment)
2- execute the command: mvn clean
3- execute the command: mvn install
4- execute the command: mvn package (This create an artefact that we can share with test team. This artefact will be in the target folder and will call bioMedical-0.0.2-SNAPSHOT.jar)
5- execute the command: java -jar target/bioMedical-0.0.2-SNAPSHOT.jar  (this command is about to test the application)
6- Open the browser on localhost:8082
