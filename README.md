# Player Ranking Management Web Project

## Overview

This web project is designed to manage player ranking data, offering functionalities for CRUD (Create, Read, Update, Delete) operations on player records. It consists of three main parts: backend, frontend, and data crawling.

## Backend

The backend of the project is implemented using Plumber in R and PostgreSQL programming language. It includes two files:

1. **server.R**: This file contains the implementation of the Plumber API endpoints to handle HTTP requests related to player data management.

2. **run.R**: This script is used to run the Plumber API on port 8000.

### API Endpoints

- **GET `/show`**: Retrieves existing player data from the Player table in the database and returns it in JSON format.

- **POST `/create`**: Receives new player data from the frontend and inserts it into the Player table in the database.

- **PUT `/Update`**: Receives updated player data from the frontend and updates the corresponding record in the Player table in the database.

- **DELETE `/delete`**: Receives the MSSV (unique identifier) of a player from the frontend and deletes the corresponding record from the Player table in the database.

## Frontend

The frontend of the project is developed using React JS. To set up the frontend, you need to install Node.js first and then use `create-react-app` to initialize a React.js project. The main file for the frontend is `test.js`.

## Data Crawling

In addition to managing player data, the project also includes a data crawling component implemented using Rselenium. This component is responsible for extracting data from a web source. Note that for Rselenium, you need to download the necessary dependencies.

## Setup Instructions

To set up the project:

1. Install Node.js and npm.
2. Initialize a React.js project using `create-react-app`.
3. Install required R packages for Plumber and PostgreSQL.
4. Ensure PostgreSQL is installed and running, create a database named `player_ranking`, and import the schema for the `Player` table.
5. Run the backend using `run.R` to start the Plumber API on port 8000.
6. Implement frontend components and functionalities in React.js.
7. Set up Rselenium for data crawling by downloading the necessary dependencies.

## Downloads

### ChromeDriver

You can download the latest version of ChromeDriver from the [ChromeDriver Downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads) page. Choose the appropriate version for your operating system.

### Java JDK 1.8

You can download Java JDK 1.8 from the [Java SE Development Kit 8 Downloads](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) page. Make sure to select the correct version for your operating system.

Ensure you download the appropriate versions compatible with your operating system.

## Contributor

- Nguyen Manh Tuan

Contributions, bug reports, and feature requests are welcome.

## License

This project is licensed under the [MIT License](LICENSE).
