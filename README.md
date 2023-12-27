# FastAPI_Manager_Erechenko
## Backend

Бэкэнд проекта выполнен на языке Python. 
База данных создана с помощью SQLAlchemy. 
Фреймворк для создания RESTful API - FastAPI. 
Для работы фронтенда необходимо, чтобы бэкенд был запущен.

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

Фронтенд проекта выполнен с использованием React.
Стили каждого компонента изменяются в соответствующем .css.
График навыков использует библиотеку Chart.js.

### Usage

### `git clone https://github.com/Alex5067/FastAPIManager.git src`
### `cd src/docker`
### `docker-compose up`
