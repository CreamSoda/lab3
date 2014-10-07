Лабораторная работа 3. Вариант 10: Сайт с расписанием занятий студентов. 
=====

Постановка задачи
-----------------

Нужно реализовать веб-приложение в соответствии с вариантом задания (Расписание занятий). Варианты совпадают с ЛР №2. Технологии, которые нужно использовать: 

- фреймворк Ruby On Rails
- ХД mongodb или couchdb

Деплой приложения
-------

1. Загрузить проект из репозитория git:

  ```
  git clone https://github.com/CreamSoda/lab3.git
  ```
2. Перейти в директорию проекта:

  ```
  cd lab3
  ```
3. Выполнить следующую команду:

  ```
  bundle install
  ```
4. Создать базу данных для приложения:

  ```shell
  mongo < db/create_db
  ```
5. Поднять сервер:

  ```
  rails server
  ```
6. Перейти по следующему адресу:

  [http://localhost:3000](http://localhost:3000)

7. Действия по редактированию данных доступны только администратору. Логин - **admin**, пароль - **admin**. Работа с группами доступна при просмотре факультетов, работа с парами - при просмотре групп.