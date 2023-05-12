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

![Alt-текст](https://i.imgur.com/I8ZJ6Ss.jpeg)

:white_check_mark: Вывести категории товаров (а так же название, цену и кол-во),
в которых общая стоимость товаров >= 200 и количество товаров <= 10:

![Alt-текст](https://i.imgur.com/WU2JLeC.jpeg)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

### JOIN
#### Диаграмма связей
![Alt-текст](https://i.imgur.com/Bbpve21.jpeg "Диаграмма")

:white_check_mark: Имена и адреса (включая город и страну) покупателей, которые сделали покупку 6 апреля 2022:

![Alt-текст](https://i.imgur.com/elGtom6.jpeg)

:white_check_mark: Наименование, цена, категория и производитель товаров, которые дороже 100:

![Alt-текст](https://i.imgur.com/DsnWnul.jpeg)

:white_check_mark: Покупатели из Минска:

![Alt-текст](https://i.imgur.com/hYw0DGm.jpeg)

:white_check_mark: Все товары с их категориями, сортировка по названию категории:

![Alt-текст](https://i.imgur.com/WMh2mFP.jpeg)

:white_check_mark: Покупатели из России с их городом. Сортировка имён по алфавиту:

![Alt-текст](https://i.imgur.com/PUrhrSn.jpeg)

:white_check_mark: Список адресов и количество покупателей из них:

![Alt-текст](https://i.imgur.com/DNiP5ph.jpeg)

:white_check_mark: Список городов и количество покупателей из них:

![Alt-текст](https://i.imgur.com/kbvYWWc.jpeg)

:white_check_mark: Категории, в которых нет товаров:

![Alt-текст](https://i.imgur.com/8URa1Pb.jpeg)

:white_check_mark: Все товары и все категории (включая те, в которых нет товаров):

![Alt-текст](https://i.imgur.com/M1wVBoH.jpeg)

:white_check_mark: Все товары и категории (включая те товары, у которых нет категории):

![Alt-текст](https://i.imgur.com/lrlTox4.jpeg)

:white_check_mark: Покупатели, у которых не заполнен адрес:

![Alt-текст](https://i.imgur.com/QlNc8uD.jpeg)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

### Update
#### Insert
:white_check_mark: Добавление строк в таблицу и заполнение их значениями:

![Alt-текст](https://i.imgur.com/B5WEwkM.jpeg)

:white_check_mark: В связанных таблицах. Добавление в таблицу unactive_user пользователей, которые не совершали ни одной покупки:

![Alt-текст](https://i.imgur.com/TnfuYCR.jpeg)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Set
:white_check_mark: Обновление данных в ячейках:

![Alt-текст](https://i.imgur.com/lrZGeOy.jpeg)

:white_check_mark: В связанных таблицах. Добавление названий категорий к названию товаров.

![Alt-текст](https://i.imgur.com/oCYUAeB.jpeg)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Change
:white_check_mark: Переименование полей:

![Alt-текст](https://i.imgur.com/YjX0ocn.jpeg)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

### Delete
[:arrow_up:Вернуться к оглавлению](#оглавление)
