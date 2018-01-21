# Running SonarQube within Docker
Simple demonstration of running SonarQube within Docker

## Setup
Rename the `.env-example` to `.env` and change the values to whatever you like. This will get you up and running with sonarqube quickly but it also means sonarqube will have *superuser* privilages when accessing the postgres service.

## Run
To start run:
```
docker-compose up -d
```

To stop run
```
docker-compose down
```