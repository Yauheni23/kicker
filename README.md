# Kicker
## About the application
    Приложение преднозначенно для ведения статистики по кикеру.
###### Возможности:
* Создавать игроков;
* Создавать команды;
* Добавлять игроков в команды
* Добавлять результаты игр
###### Статистика:
* по игрокам
* по командам
* по играм

## Technologies:
* FrontEnd: Angular 8, HTML5, CSS3, ES6
* Mobile application: React Native, Expo
* BackEnd: NodeJS, Express, Sequelize, PostgreSQL

## Installation:
Requirements: NodeJS v12+, npm v6.5+
* BackEnd:
1. ```cd/kicker-backend```
2. ```npm install```
3. Create file ***.env***, add credentials for DB(PostgreSQL) in the file.
4. ```npm run database```
5. ```npm start```
* FrontEnd: 
1. ```cd/kicker-angular```
2. ```npm install```
3. Change url address in the file *src/app/constant.ts*
