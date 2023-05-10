# SQL
Привет!) Здесь о том, как я изучала запросы SQL и работала в MySQL Workbench и Shell в рамках интенсива от "Школы седого тестировщика".

## Оглавление
1. [Create](#create)
2. [Read](#create)
    1. [Простые селекты](#простые-селекты)
    2. [Групповые запросы](#групповые-запросы)
    3. [Вложенные запросы](#вложенные-запросы)
    4. [Джоины](#Join)
3. [Update](#update)
    1. [Insert](#insert)
    2. [Set](#set)
    3. [Change](#change)
4. [Delete](#delete)

_____
### Create

CREATE TABLE название таблицы (
название столбца1 INT PRIMARY KEY AUTO_INCREMENT,
название столбца2 тип данных,
название столбца3 тип данных
);

### Read
#### Простые селекты
:white_check_mark: Список баз данных

![image](https://github.com/HappyToster/SQL/assets/97261554/350da904-e02c-475d-9c81-3c0da632fe93)

:white_check_mark: Список таблиц в базе

![image](https://github.com/HappyToster/SQL/assets/97261554/7eb24c5a-d74f-4870-ac65-95ce79dfc945)

:white_check_mark: Выборка всех данных из таблицы

![image](https://github.com/HappyToster/SQL/assets/97261554/bb8e0513-88d1-4f98-816b-e2d5ffeaca30)

:white_check_mark: Выборка определенных столбцов из таблицы

![image](https://github.com/HappyToster/SQL/assets/97261554/c78a962a-43f3-4cae-9f23-4cc90f73dc98)

:white_check_mark: Товары производителя с id "1"

![image](https://github.com/HappyToster/SQL/assets/97261554/4136d2ca-aa09-4914-b429-7fbca3bbfd3f)

:white_check_mark: Поменять название столбца при выводе

![image](https://github.com/HappyToster/SQL/assets/97261554/3057a83b-df78-428b-97cf-13edd3b377f3)

:white_check_mark: ДОБАВИТЬ ОПЕРАЦИЮ``` ПРОПУСТИЛА * 100

![image](https://github.com/HappyToster/SQL/assets/97261554/679a729e-7d31-4470-9a29-e176777cdc74)

:white_check_mark: Товары с ценой > 500

![image](https://github.com/HappyToster/SQL/assets/97261554/536188fd-e487-40ca-9333-dc9d22d18ed9)

:white_check_mark: Товары с весом < 60 и ценой > 100

![image](https://github.com/HappyToster/SQL/assets/97261554/1d5d1494-c299-4cf4-b4ce-86e9163d6bfb)

:white_check_mark: Товары производителей с id "1" или "2" и ценой > 20

![image](https://github.com/HappyToster/SQL/assets/97261554/0711a9bc-0edf-4d9e-9219-c2174c8c3d1d)

:white_check_mark: Товары с id между "2" и "4" включительно

![image](https://github.com/HappyToster/SQL/assets/97261554/a763736c-02db-4d06-9052-4311e1ff7223)
										
:white_check_mark: Исключить товары производителей с id "1" и "2"

![image](https://github.com/HappyToster/SQL/assets/97261554/7b52e790-fcc1-4233-828d-088c06014db3)
							
:white_check_mark: Товары с ценой 96 и 62

![image](https://github.com/HappyToster/SQL/assets/97261554/e403382c-dae1-4ae9-a92e-e7f8d5ce07f4)

:white_check_mark: По весу по возрастанию

![image](https://github.com/HappyToster/SQL/assets/97261554/8ef487eb-549c-4d7f-928c-0f50c78ed66e)

:white_check_mark: По цене по убыванию

![image](https://github.com/HappyToster/SQL/assets/97261554/07da9260-a944-41a4-93a0-b38b05b8e473)

:white_check_mark: Исключить товары производителя с id "2"

![image](https://github.com/HappyToster/SQL/assets/97261554/9e0bbc7b-247f-4681-8931-b9b7241361ab)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Групповые запросы
:white_check_mark: Количество позиций по определенной категории, сортировка по названию категории (по алфавиту)

![image](https://github.com/HappyToster/SQL/assets/97261554/cb90afc4-38e4-4410-be39-8cb89c376e89)

:white_check_mark: Общая стоимость и количество позиций по категориям

![image](https://github.com/HappyToster/SQL/assets/97261554/9b828ec2-fbf9-436a-a3a6-9c31439315c2)

:white_check_mark: Общая стоимость всех товаров из категории Электроинструмент

![image](https://github.com/HappyToster/SQL/assets/97261554/69c8f926-201c-406f-98d8-d50d8f4cb88f)

```Общая стоимость и количество товаров в категории Бокорезы, кусачки```

![image](https://github.com/HappyToster/SQL/assets/97261554/b9530650-9ffa-43e7-8b33-754aea90c7dd)

```Минимальная стоимость товара в категории Модельный скотч```

![image](https://github.com/HappyToster/SQL/assets/97261554/44f83f7e-7b97-470f-8f67-c22414de9f04)

```Средняя стоимость товаров в категориях```

![image](https://github.com/HappyToster/SQL/assets/97261554/bd114957-df0b-4791-8c85-8a3826353271)

```Общее количество товаров по категориям```

![image](https://github.com/HappyToster/SQL/assets/97261554/a5c5c508-b412-488d-8595-daa1c0d2843d)

```Общее количество товаров в магазине```

![image](https://github.com/HappyToster/SQL/assets/97261554/7cb53c4b-fe11-4137-a887-4d82b5bfbf95)

```Средняя стоимость товаров в магазине```

![image](https://github.com/HappyToster/SQL/assets/97261554/2e616ac3-9acf-4ee6-9a78-30d4afdbfb4b)

```Максимальная и минимальная цена товаров, общая сумма которых >10000```

![image](https://github.com/HappyToster/SQL/assets/97261554/e5ff54b2-f0bb-4b0f-88ea-314609615b57)

```Максимальная и минимальная цена товаров, общая сумма которых больше 10000, исключая категорию Электроинструмент```

![image](https://github.com/HappyToster/SQL/assets/97261554/c64b0f44-e9a0-41ee-8dac-69cd6b9b6aff)

```Товары с минимальной стоимостью в каждой категории```

![image](https://github.com/HappyToster/SQL/assets/97261554/76e3c3cb-345d-48dd-888f-a7914f1fd0f4)

```Товар с наименьшей ценой```

![image](https://github.com/HappyToster/SQL/assets/97261554/95514843-55d3-4439-80f1-62cb370929c7)

```Сумма товаров в категории меньше минимальной средней стоимости```

![image](https://github.com/HappyToster/SQL/assets/97261554/1f22f9ab-939f-4984-ae51-4a7a938f7000)

```Сумма товаров в категории больше максимальной средней стоимости```

![image](https://github.com/HappyToster/SQL/assets/97261554/2b071176-a06e-4950-82ca-8f447b4650d9)

```Сумма товаров в категории меньше максимальной средней стоимости```

![image](https://github.com/HappyToster/SQL/assets/97261554/ed8cffc4-152f-4c8e-acdb-a13153f843a8)

```Сумма товаров в категории меньше максимальной средней стоимости```

![image](https://github.com/HappyToster/SQL/assets/97261554/8441b632-600d-4098-a529-aa9c04d2e168)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Вложенные запросы
```Товар с наименьшей ценой```

![image](https://github.com/HappyToster/SQL/assets/97261554/32a60a4d-f489-43e7-a329-d97a3c8735c2)

```Вывести категории товаров (а так же название, цену и кол-во), в которых общая стоимость товаров >= 200 и количество товаров <= 10```

![image](https://github.com/HappyToster/SQL/assets/97261554/c715664c-4f4e-4bda-bbc3-65d56455e807)

```Изменить запрос для таблицы product таким образом, чтобы добавить условие: год выпуска должен быть больше 2018 года.```

![image](https://github.com/HappyToster/SQL/assets/97261554/52640000-9072-4099-a96f-74f0944e8198)

```Составить запрос для таблицы product: Показать только те товары, у которых общая стоимость меньше самой большой средней стоимости товара каждой категории.```

![image](https://github.com/HappyToster/SQL/assets/97261554/b817e77a-b19a-4d28-a958-f31dca98919a)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Join
```Покажи имена и адреса (включая город и страну) покупателей, которые сделали покупку 6 апреля 2022```

![image](https://github.com/HappyToster/SQL/assets/97261554/ad3bf481-0b20-4964-a414-66ad03b232ac)

```Покажи наименование, цену, категорию и производителя товаров, которые дороже 100р```

![image](https://github.com/HappyToster/SQL/assets/97261554/78b52fc0-2534-40c5-9d77-034611dbb0ad)

```Покажи покупателей из Минска```

![image](https://github.com/HappyToster/SQL/assets/97261554/e4cb6ac1-aee7-4dec-80c4-c5036994eeb2)

```Покажи все товары с их категориями, сортировка по названию категории```

![image](https://github.com/HappyToster/SQL/assets/97261554/1816276e-4824-4b82-9f36-d4b0ca6e7485)

```Покажи покупателей из России с их городом. Сортировка имён по алфавиту```

![image](https://github.com/HappyToster/SQL/assets/97261554/87e44ec3-1aa5-4044-acb7-64812557d0e5)

```Покажи список адресов и количество покупателей из них```

![image](https://github.com/HappyToster/SQL/assets/97261554/c23c8f1c-b8de-4492-a4bb-90932fc24b27)

```Покажи список городов и количество покупателей из них```

![image](https://github.com/HappyToster/SQL/assets/97261554/7c6e38ea-a29d-4b16-b7ad-36b548b45227)

```Покажи категории, в которых нет товаров```

![image](https://github.com/HappyToster/SQL/assets/97261554/68258ee5-f9b3-4d5d-90a4-357a1cf0d199)

```Покажи все товары и все категории (включая те, в которых нет товаров)```

![image](https://github.com/HappyToster/SQL/assets/97261554/0485ce15-e887-4eee-af8a-c75a4ef404db)

```Покажи все товары и категории (включая те товары, у которых нет категории)```

![image](https://github.com/HappyToster/SQL/assets/97261554/cb2f8fbb-cc42-4b61-aa80-6dbe05917b1c)

```Покажи покупателей, у которых не заполнен адрес```

![image](https://github.com/HappyToster/SQL/assets/97261554/4480b157-b4f5-4b5e-aa91-850b86252c2b)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

### Update
#### Insert
![image](https://github.com/HappyToster/SQL/assets/97261554/71c6d425-3392-4a24-95bd-8fec4979017e)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Set
```Изменение данных в ячейках родительской таблицы```

![image](https://github.com/HappyToster/SQL/assets/97261554/b6c5e449-13ba-40a8-9462-6ea12aad8f02)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

#### Change
```Переименование полей родительской таблицы```

![image](https://github.com/HappyToster/SQL/assets/97261554/699a7bc4-737c-4721-9fdd-f3341a1c934f)

[:arrow_up:Вернуться к оглавлению](#оглавление)

_____

### Delete
[:arrow_up:Вернуться к оглавлению](#оглавление)
