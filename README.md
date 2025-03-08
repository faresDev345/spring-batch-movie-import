# Spring Batch File to Database Migration

This project demonstrates how to use Spring Batch to migrate data from a file (CSV/TXT) to a MySQL database.

## Features
- Reads data from a file.
- Processes the data using a custom processor.
- Writes the data to a MySQL database.

## Technologies Used
- Spring Boot
- Spring Batch
- Spring Data JPA
- MySQL

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/faresDev345/spring-batch-movie-import.git
 
 

    Cloner le dépôt :

    git clone https://github.com/faresDev345/spring-batch-movie-import.git
    cd pring-batch-movie-import

    Configurer l'environnement : Créer un fichier .env avec les mêmes entrées que .env.example :

    MYSQL_URL=jdbc:mysql://localhost:3306/mydb
    MYSQL_USERNAME=utilisateur
    MYSQL_PASSWORD=motdepasse
    MYSQL_DATABASE=basededonnees

    POSTGRES_URL=jdbc:postgresql://localhost:5432/mydb
    POSTGRES_USERNAME=postgres
    POSTGRES_PASSWORD=motdepasse
    POSTGRES_DATABASE=basededonnees

    Job_Name=copyMovieJob

    Compiler le projet :

    ./mvnw clean install

    Exécuter l'application :

    ./mvnw spring-boot:run

Exécution du Job Batch

Vous pouvez démarrer le job batch de migration de données via terminal ou cmd : java -jar com.app.data.entry-0.0.1-SNAPSHOT.jar
