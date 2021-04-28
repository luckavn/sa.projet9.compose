# Fymr App - Composse

Fymr is a medical app that allows professionals to : 
- Create, edit or delete :
    - Patients
    - Notes
- Calculate a risk for a patient
    
This app concerns all 5 micro-services.

## Prerequisite to run it (Local)

- Java 11 JDK (or +)
- Maven 3.5.X (or +)
- Docker Desktop
- MySQL
- MongoDB 
- NodeJS
- npm + Angular Cli

## Run apps (Docker)

```
- Git clone all projects (see above)
- Verify docker-compose file in docker-compose project and adapt links for projects
- Launch Docker 
- For Windows users only : modify your hosts file and expose services name with your localhost
- Open command terminal at root of compose
- Launch "docker-compose up"

```

## Contributing
Github repo is public, you can fork it and make improvements.
Please make sure to update tests as appropriate.

https://github.com/luckavn/sa.projet9.patientapi
https://github.com/luckavn/sa.projet9.notesapi
https://github.com/luckavn/sa.projet9.riskapi
https://github.com/luckavn/sa.projet9.gatewayapi
https://github.com/luckavn/sa.projet9.angularclient
https://github.com/luckavn/sa.projet9.compose