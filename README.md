# SQL
Привет!) Здесь о том, как я изучала запросы SQL и работала в MySQL Workbench и Shell в рамках интенсива от "Школы седого тестировщика".

## Оглавление
1. [Create](#create)
2. [Read](#create)
    1. [Простые селекты](#простые-селекты)
    2. [Групповые запросы](#групповые-запросы)
    3. [Вложенные запросы](#вложенные-запросы)
    4. [Джойны](#Join)
        1. [Диаграмма связей](#диаграмма-связей)
3. [Update](#update)
    1. [Insert](#insert)
    2. [Set](#set)
    3. [Change](#change)
4. [Delete](#delete)

_____
### Create
:white_check_mark: Создание таблицы:

![image](https://github.com/HappyToster/SQL/assets/97261554/a8f28f36-3520-47a6-8017-6cfb9ef33b1f)

### Read
#### Простые селекты
:white_check_mark: Список баз данных:

![image](https://github.com/HappyToster/SQL/assets/97261554/350da904-e02c-475d-9c81-3c0da632fe93)

:white_check_mark: Список таблиц в базе:

![image](https://github.com/HappyToster/SQL/assets/97261554/7eb24c5a-d74f-4870-ac65-95ce79dfc945)

:white_check_mark: Выборка всех данных из таблицы:

![image](https://github.com/HappyToster/SQL/assets/97261554/bb8e0513-88d1-4f98-816b-e2d5ffeaca30)

:white_check_mark: Выборка определенных столбцов из таблицы:

![image](https://github.com/HappyToster/SQL/assets/97261554/c78a962a-43f3-4cae-9f23-4cc90f73dc98)

:white_check_mark: Товары производителя с id "1":

![image](https://github.com/HappyToster/SQL/assets/97261554/0eb10fe5-c1fc-4799-ae4e-9a64bafe1734)

:white_check_mark: Поменять название столбца при выводе:

![image](https://github.com/HappyToster/SQL/assets/97261554/3057a83b-df78-428b-97cf-13edd3b377f3)

:white_check_mark: Умножить вес каждого товара на 100 и вывести как результат:

![image](https://github.com/HappyToster/SQL/assets/97261554/c8e5be2a-f1d6-4b2a-9910-0a04ec5d9593)

:white_check_mark: Товары с ценой > 500:

![image](https://github.com/HappyToster/SQL/assets/97261554/536188fd-e487-40ca-9333-dc9d22d18ed9)

:white_check_mark: Товары с весом < 60 и ценой > 100:

![image](https://github.com/HappyToster/SQL/assets/97261554/1d5d1494-c299-4cf4-b4ce-86e9163d6bfb)

:white_check_mark: Товары производителей с id "1" или "2" и ценой > 20:

![image](https://github.com/HappyToster/SQL/assets/97261554/f2799fbd-1c63-450e-a08a-1c65ce54aed1)

:white_check_mark: Товары с id между "2" и "4" включительно:

![image](https://github.com/HappyToster/SQL/assets/97261554/61759d6c-25b5-48fb-88e6-a5b0b048fc38)

:white_check_mark: Исключить товары производителей с id "1" и "2":

![image](https://github.com/HappyToster/SQL/assets/97261554/0741696d-2de4-4f47-828c-657e1dca9e12)

:white_check_mark: Товары с ценой 96 и 62:

![image](https://github.com/HappyToster/SQL/assets/97261554/e403382c-dae1-4ae9-a92e-e7f8d5ce07f4)

:white_check_mark: По весу по возрастанию:

![image](https://github.com/HappyToster/SQL/assets/97261554/8ef487eb-549c-4d7f-928c-0f50c78ed66e)

:white_check_mark: По цене по убыванию:

![image](https://github.com/HappyToster/SQL/assets/97261554/07da9260-a944-41a4-93a0-b38b05b8e473)

:white_check_mark: Исключить товары производителя с id "2":

![image](https://github.com/HappyToster/SQL/assets/97261554/a4e17470-8af9-4ac7-800d-8b0cfc2242c5)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Групповые запросы
:white_check_mark: Количество позиций по определенной категории, сортировка по названию категории (по алфавиту):

![image](https://github.com/HappyToster/SQL/assets/97261554/cb90afc4-38e4-4410-be39-8cb89c376e89)

:white_check_mark: Общая стоимость и количество позиций по категориям:

![image](https://github.com/HappyToster/SQL/assets/97261554/9b828ec2-fbf9-436a-a3a6-9c31439315c2)

:white_check_mark: Общая стоимость всех товаров из категории "Электроинструмент":

![image](https://github.com/HappyToster/SQL/assets/97261554/69c8f926-201c-406f-98d8-d50d8f4cb88f)

:white_check_mark: Общая стоимость и количество товаров в категории "Бокорезы, кусачки":

![image](https://github.com/HappyToster/SQL/assets/97261554/b9530650-9ffa-43e7-8b33-754aea90c7dd)

:white_check_mark: Минимальная стоимость товаров в категории "Модельный скотч":

![image](https://github.com/HappyToster/SQL/assets/97261554/44f83f7e-7b97-470f-8f67-c22414de9f04)

:white_check_mark: Средняя стоимость товаров в категориях:

![image](https://github.com/HappyToster/SQL/assets/97261554/bd114957-df0b-4791-8c85-8a3826353271)

:white_check_mark: Общее количество товаров по категориям:

![image](https://github.com/HappyToster/SQL/assets/97261554/a5c5c508-b412-488d-8595-daa1c0d2843d)

:white_check_mark: Общее количество товаров в магазине:

![image](https://github.com/HappyToster/SQL/assets/97261554/7cb53c4b-fe11-4137-a887-4d82b5bfbf95)

:white_check_mark: Средняя стоимость товаров в магазине:

![image](https://github.com/HappyToster/SQL/assets/97261554/2e616ac3-9acf-4ee6-9a78-30d4afdbfb4b)

:white_check_mark: Максимальная и минимальная цена товаров, общая сумма которых >10000:

![image](https://github.com/HappyToster/SQL/assets/97261554/e5ff54b2-f0bb-4b0f-88ea-314609615b57)

:white_check_mark: Максимальная и минимальная цена товаров, общая сумма которых больше 10000,
исключая категорию "Электроинструмент":

![image](https://github.com/HappyToster/SQL/assets/97261554/c64b0f44-e9a0-41ee-8dac-69cd6b9b6aff)

:white_check_mark: Товары с минимальной стоимостью в каждой категории:

![image](https://github.com/HappyToster/SQL/assets/97261554/76e3c3cb-345d-48dd-888f-a7914f1fd0f4)

:white_check_mark: Товар с наименьшей ценой:

![image](https://github.com/HappyToster/SQL/assets/97261554/95514843-55d3-4439-80f1-62cb370929c7)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Вложенные запросы

:white_check_mark: Товар с наименьшей ценой:

![image](https://github.com/HappyToster/SQL/assets/97261554/32a60a4d-f489-43e7-a329-d97a3c8735c2)

:white_check_mark: Вывести категории товаров (а так же название, цену и кол-во),
в которых общая стоимость товаров >= 200 и количество товаров <= 10:

![image](https://github.com/HappyToster/SQL/assets/97261554/c715664c-4f4e-4bda-bbc3-65d56455e807)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

### JOIN
#### Диаграмма связей
![Alt-текст](https://i.imgur.com/Bbpve21.jpeg "Диаграмма")

:white_check_mark: Имена и адреса (включая город и страну) покупателей, которые сделали покупку 6 апреля 2022:

![image](https://github.com/HappyToster/SQL/assets/97261554/ad3bf481-0b20-4964-a414-66ad03b232ac)

:white_check_mark: Наименование, цена, категория и производитель товаров, которые дороже 100:

![image](https://github.com/HappyToster/SQL/assets/97261554/78b52fc0-2534-40c5-9d77-034611dbb0ad)

:white_check_mark: Покупатели из Минска:

![image](https://github.com/HappyToster/SQL/assets/97261554/e4cb6ac1-aee7-4dec-80c4-c5036994eeb2)

:white_check_mark: Все товары с их категориями, сортировка по названию категории:

![image](https://github.com/HappyToster/SQL/assets/97261554/1816276e-4824-4b82-9f36-d4b0ca6e7485)

:white_check_mark: Покупатели из России с их городом. Сортировка имён по алфавиту:

![image](https://github.com/HappyToster/SQL/assets/97261554/87e44ec3-1aa5-4044-acb7-64812557d0e5)

:white_check_mark: Список адресов и количество покупателей из них:

![image](https://github.com/HappyToster/SQL/assets/97261554/c23c8f1c-b8de-4492-a4bb-90932fc24b27)

:white_check_mark: Список городов и количество покупателей из них:

![image](https://github.com/HappyToster/SQL/assets/97261554/7c6e38ea-a29d-4b16-b7ad-36b548b45227)

:white_check_mark: Категории, в которых нет товаров:

![image](https://github.com/HappyToster/SQL/assets/97261554/68258ee5-f9b3-4d5d-90a4-357a1cf0d199)

:white_check_mark: Все товары и все категории (включая те, в которых нет товаров):

![image](https://github.com/HappyToster/SQL/assets/97261554/0485ce15-e887-4eee-af8a-c75a4ef404db)

:white_check_mark: Все товары и категории (включая те товары, у которых нет категории):

![image](https://github.com/HappyToster/SQL/assets/97261554/cb2f8fbb-cc42-4b61-aa80-6dbe05917b1c)

:white_check_mark: Покупатели, у которых не заполнен адрес:

![image](https://github.com/HappyToster/SQL/assets/97261554/4480b157-b4f5-4b5e-aa91-850b86252c2b)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

### Update
#### Insert
:white_check_mark: Добавление строк в таблицу и заполнение их значениями:

![image](https://github.com/HappyToster/SQL/assets/97261554/71c6d425-3392-4a24-95bd-8fec4979017e)

:white_check_mark: В связанных таблицах. Добавление в таблицу unactive_user пользователей, которые не совершали ни одной покупки:

![image](https://github.com/HappyToster/SQL/assets/97261554/1b89682d-ef6f-40d8-a1df-ec74cc85934f)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Set
:white_check_mark: Обновление данных в ячейках:

![image](https://github.com/HappyToster/SQL/assets/97261554/e977584a-16af-4fd1-861d-2b65c24dd43c)

:white_check_mark: В связанных таблицах:

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Change
:white_check_mark: Переименование полей:

![image](https://github.com/HappyToster/SQL/assets/97261554/699a7bc4-737c-4721-9fdd-f3341a1c934f)

:white_check_mark: В связанных таблицах:

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

### Delete
[:arrow_up:Вернуться к оглавлению](#оглавление)
