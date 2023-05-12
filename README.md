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

![Alt-текст](https://github-production-user-asset-6210df.s3.amazonaws.com/97261554/237845246-9a3765d7-060b-441f-b705-89c87a8f4da0.png)

### Read
#### Простые селекты
:white_check_mark: Список баз данных:

![Alt-текст](https://i.imgur.com/brm4cdd.jpeg)

:white_check_mark: Список таблиц в базе:

![Alt-текст](https://i.imgur.com/u6uodG5.jpeg)

:white_check_mark: Выборка всех данных из таблицы:

![Alt-текст](https://i.imgur.com/YOY66x5.jpeg)

:white_check_mark: Выборка определенных столбцов из таблицы:

![Alt-текст](https://i.imgur.com/lLpb5SA.jpeg)

:white_check_mark: Товары производителя с id "1":

![Alt-текст](https://i.imgur.com/q5sC2xk.jpeg)

:white_check_mark: Поменять название столбца при выводе:

![Alt-текст](https://i.imgur.com/ppFFBPL.jpeg)

:white_check_mark: Умножить вес каждого товара на 100 и вывести как результат:

![Alt-текст](https://i.imgur.com/ASw8dz2.jpeg)

:white_check_mark: Товары с ценой > 500:

![Alt-текст](https://i.imgur.com/ckWv4uC.jpeg)

:white_check_mark: Товары с весом < 60 и ценой > 100:

![Alt-текст](https://i.imgur.com/cJVTGo6.jpeg)

:white_check_mark: Товары производителей с id "1" или "2" и ценой > 20:

![Alt-текст](https://i.imgur.com/XZbQrwz.jpeg)

:white_check_mark: Товары с id между "2" и "4" включительно:

![Alt-текст](https://i.imgur.com/x6UcI1z.jpeg)

:white_check_mark: Исключить товары производителей с id "1" и "2":

![Alt-текст](https://i.imgur.com/qkY8v9j.jpeg)

:white_check_mark: Товары с ценой 96 и 62:

![Alt-текст](https://i.imgur.com/pnz9A3O.jpeg)

:white_check_mark: По весу по возрастанию:

![Alt-текст](https://i.imgur.com/kECUa1Y.jpeg)

:white_check_mark: По цене по убыванию:

![Alt-текст](https://i.imgur.com/47fjf2w.jpeg)

:white_check_mark: Исключить товары производителя с id "2":

![Alt-текст](https://i.imgur.com/brm4cdd.jpeg)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Групповые запросы
:white_check_mark: Количество позиций по определенной категории, сортировка по названию категории (по алфавиту):

![Alt-текст](https://i.imgur.com/66ODg1H.jpeg)

:white_check_mark: Общая стоимость и количество позиций по категориям:

![Alt-текст](https://i.imgur.com/q0O19R3.jpeg)

:white_check_mark: Общая стоимость всех товаров из категории "Электроинструмент":

![Alt-текст](https://i.imgur.com/eS8N5Gd.jpeg)

:white_check_mark: Общая стоимость и количество товаров в категории "Бокорезы, кусачки":

![Alt-текст](https://i.imgur.com/JRVxaEr.jpeg)

:white_check_mark: Минимальная стоимость товаров в категории "Модельный скотч":

![Alt-текст](https://i.imgur.com/jHMRrer.jpeg)

:white_check_mark: Средняя стоимость товаров в категориях:

![Alt-текст](https://i.imgur.com/0nNh7vZ.jpeg)

:white_check_mark: Общее количество товаров по категориям:

![Alt-текст](https://i.imgur.com/0oqpurP.jpeg)

:white_check_mark: Общее количество товаров в магазине:

![Alt-текст](https://i.imgur.com/ySq8FoD.jpeg)

:white_check_mark: Средняя стоимость товаров в магазине:

![Alt-текст](https://i.imgur.com/2P5QwFe.jpeg)

:white_check_mark: Максимальная и минимальная цена товаров, общая сумма которых >10000:

![Alt-текст](https://i.imgur.com/rcyJqZE.jpeg)

:white_check_mark: Максимальная и минимальная цена товаров, общая сумма которых больше 10000,
исключая категорию "Электроинструмент":

![Alt-текст](https://i.imgur.com/GEjtjae.jpeg)

:white_check_mark: Товары с минимальной стоимостью в каждой категории:

![Alt-текст](https://i.imgur.com/5193Ex9.jpeg)

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

:white_check_mark: В связанных таблицах. Добавление названий категорий к названию товаров.

![image](https://github.com/HappyToster/SQL/assets/97261554/bcd02496-eacd-407d-a388-7c0212504009)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Change
:white_check_mark: Переименование полей:

![image](https://github.com/HappyToster/SQL/assets/97261554/699a7bc4-737c-4721-9fdd-f3341a1c934f)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

### Delete
[:arrow_up:Вернуться к оглавлению](#оглавление)
