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

Сначала вам нужно создать администратора с электронной почтой и паролем на бэкенде, затем вы сможете войти на фронтенд и увидеть всех пользователей из базы данных.
Измените .env на предпочтительную ветку и порты.
Откройте http://localhost:8000/docs для просмотра методов API.

Страница будет перезагружаться, если вы вносите правки.
На странице показаны все доступные варианты CRUD для бэкенда. Использование опции "Try it out" для каждой операции изменяет файл database.db или используйте Postman.

Откройте http://localhost:3000 для просмотра веб-формы, позволяющей проверять пользователей. Страница будет перезагружаться при внесении правок.
