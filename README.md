# Kicker
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

## Технологии:
* FrontEnd: Angular 8, HTML5, CSS3, ES6
* Mobile application: React Native, Expo
* BackEnd: NodeJS, Express, Sequelize, PostgreSQL

## Инструкция по установке:
Требования: NodeJS v12+, npm v6.5+

<code>git clone https://github.com/Yauheni23/kicker.git</code>

* BackEnd:
1. Войти в папку: ```cd/kicker-backend```
2. Установить зависимости: ```npm install```
3. Создать БД(PostgreSQL)
4. Создать файл ***.env*** и заполнить по примеру ***.env.example***
5. Сгенирировать БД командой: ```npm run database```
6. Запустить сервер: ```npm start```
* FrontEnd: 
1. Войти в папку: ```cd/kicker-angular```
2. Установить зависимости: ```npm install```
3. Изменить ***serverAddress*** на ваш адрес сервера в файле *src/app/constant.ts* 
4. Запустить приложение: ```npm start```
* Mobile application
(Требование: bucket на AWS с директорией image c разрешением на чтение файлов):
1. Войти в папку: ```cd/kicker-react-native```
2. Установить зависимости: ```yarn```
3. Изменить ***serverAddress*** на ваш адрес сервера в файле *constants/server.js* 
4. Создать файл ***env.js*** и заполнить по примеру ***env.example.js***
5. Запустить приложение: ```yarn start```
6. Установить на ваш мобильный телефон приложение ***Expo*** из Google Play
7. Просканировать код

## Лицензия 
The MIT License

Copyright (c) 2020 Yauheni Yarmolich.
