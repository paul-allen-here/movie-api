# movie-api
Test task on node for movies. 


Инструкция:

Склонировать репозиторий.
В корневой папке movie-api создать файл <.env>
==============================================

В файле нужен 1 параметр
=============================================================

API_KEY=cb4abcaa383d8dcc239745f0cbf9f7da

В корневой папке movie-api, ввести команду:
===========================================
npm i

После завершения установки зависимостей, там же запустить скрипт app.js
=======================================================================
node app.js

В консоли должно появиться следующее:
=====================================

Server for a blog started on port  5000

MongoDB Connected

Genres ready.


Сервер запущен и работает!
==========================

api роуты для теста: (в случае если сервер запущен на localhost:5000)

localhost:5000/api/movie/:id (для киношек по id)

localhost:5000/api/movies/ (небольшая веб форма, для теста фильтров и сотрировок)

localhost:5000/api/genre/:id (роут с подсчетом рейтинга для жанра)
