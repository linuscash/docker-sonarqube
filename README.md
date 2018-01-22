# Running SonarQube within Docker
Simple demonstration of running SonarQube within Docker.

## Setup
Clone the repository. Rename the `.env-example` to `.env` and change the values to your preference.

To bring the service up, run:
```
docker-compose up -d
```
You can then navigate to http://localhost:9000/ to access the sonarqube service.

To bring the service down run:
```
docker-compose down
```

This will get you up and running with sonarqube quickly but it does mean sonarqube will use the *superuser* account within the postgres service. It is recommended to create a dedicated user with appropriate privilages for the sonarqube service to utilise.
