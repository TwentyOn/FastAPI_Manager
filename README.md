# FastAPI_Manager_Erechenko
## Backend

The project backend is made using Python.
The database was created using SQLAlchemy.
The framework for creating the RESTful API is FastAPI.
The backend needs to be running for the frontend to work.

### Models

There are 2 entities:

Admin:
*   id
*   email
*   hashedPW
*   users (relation with User)

User:
*   id
*   avatar
*   email
*   firstName
*   lastName
*   position
*   skills
*   adminId (relation with Admin)

## Frontend

The project frontend is made using React.
The styles of each component are modified in their respective .css.
The skills chart uses the Chart.js library.

### Usage

### `git clone https://github.com/Alex5067/FastAPIManager.git src`
### `cd src/docker`
### `docker-compose up`
