# Welcome in MusicalTwin! :star:
## What does this application do?
By logging in with your Spotify account, you will be able to find people with the same musical taste as yours (kinda)!

## Technology used
- React
- Java -> maven, mvc, jpa, spring-boot
- MySql
- Spotify API

:stars:

# Anteprima UI
![Foto](https://github.com/musicalTwin/client/blob/master/STILEDEFINITIVO.png?raw=true)

# Average MusicalTwin user:
![Foto](https://github.com/musicalTwin/client/blob/master/giovanni.png?raw=true)



# Development setup

### Local generated Api Docs

[http://localhost:5000/swagger-ui/index.html](http://localhost:5000/swagger-ui/index.html)


# How to run the app on local machine

> Frontend

Install [node](https://nodejs.org/en/), then into `client` directory
```
npm install
npm start
```
#### start port: [http://localhost:3000/](http://localhost:3000/)

<br />

> Backend

Install [Java](https://www.java.com)

Install [Java Development Kit](https://www.oracle.com/java/technologies/javase/jdk18-archive-downloads.html)

Install [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)

On MySQL Workbench import `server/db.sql` and on `server/src/main/resources/application.properties` insert the root password

To run (in `server`)
```
.\mvnw.cmd spring-boot:run
```

#### start port: [http://localhost:5000/](http://localhost:5000/) (if you want to change it: `server/src/main/resources/application.properties`)
