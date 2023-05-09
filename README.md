# SQL
Привет!) Здесь о том, как я изучала запросы SQL и работала в MySQL Workbench и Shell в рамках интенсива от "Школы седого тестировщика".

## Оглавление
1. [Read](#create)
    1. [Простые селекты](#простые-селекты)
    2. [Групповые запросы](#групповые-запросы)
    3. [Вложенные запросы](#вложенные-запросы)
    4. [Джоины](#Join)
2. [Update](#update)
    1. [Insert](#insert)
    2. [Set](#set)
    3. [Change](#change)
4. [Delete](#delete)

_____

### Read
#### Простые селекты
```Показать список баз данных```

![image](https://github.com/HappyToster/SQL/assets/97261554/350da904-e02c-475d-9c81-3c0da632fe93)

```Показать список таблиц в базе```

![image](https://github.com/HappyToster/SQL/assets/97261554/7eb24c5a-d74f-4870-ac65-95ce79dfc945)

```Выборка всех данных из таблицы```

![image](https://github.com/HappyToster/SQL/assets/97261554/bb8e0513-88d1-4f98-816b-e2d5ffeaca30)

```Выборка определенных столбцов из таблицы```

![image](https://github.com/HappyToster/SQL/assets/97261554/c78a962a-43f3-4cae-9f23-4cc90f73dc98)

```Выборка  по условию&&&&&&&&&```

![image](https://github.com/HappyToster/SQL/assets/97261554/4136d2ca-aa09-4914-b429-7fbca3bbfd3f)

```Поменять название столбца при выводе```

![image](https://github.com/HappyToster/SQL/assets/97261554/3057a83b-df78-428b-97cf-13edd3b377f3)

```ДОБАВИТЬ ОПЕРАЦИЮ```

![image](https://github.com/HappyToster/SQL/assets/97261554/679a729e-7d31-4470-9a29-e176777cdc74)

```ЦЕНА ВЫШЕ 500```

![image](https://github.com/HappyToster/SQL/assets/97261554/536188fd-e487-40ca-9333-dc9d22d18ed9)

```БАЛ```

![image](https://github.com/HappyToster/SQL/assets/97261554/1d5d1494-c299-4cf4-b4ce-86e9163d6bfb)

```блабла```

![image](https://github.com/HappyToster/SQL/assets/97261554/0711a9bc-0edf-4d9e-9219-c2174c8c3d1d)

```GGG```

![image](https://github.com/HappyToster/SQL/assets/97261554/5010710a-9f91-441d-ba7e-3f0aec565a31)

```LLL```

![image](https://github.com/HappyToster/SQL/assets/97261554/01ea2703-fab2-4ae8-af16-f2068b5b7c4c)

```ВЫВОДИТ ВКЛЮЧИТЕЛЬНО```

![image](https://github.com/HappyToster/SQL/assets/97261554/a763736c-02db-4d06-9052-4311e1ff7223)
										
```НЕ ТАКОЙ И НЕ ТАКОЙ. ОТСЕКАЕТ ЗНАЧЕНИЯ В СКОБКАХ```

![image](https://github.com/HappyToster/SQL/assets/97261554/7b52e790-fcc1-4233-828d-088c06014db3)
							
```ПОЯВЯТСЯ ТОЛЬКО ЗНАЧ В СКОБКАХ```

![image](https://github.com/HappyToster/SQL/assets/97261554/e403382c-dae1-4ae9-a92e-e7f8d5ce07f4)

```По возрастанию```

![image](https://github.com/HappyToster/SQL/assets/97261554/8ef487eb-549c-4d7f-928c-0f50c78ed66e)

```ПО УБЫВАНИЮ```

![image](https://github.com/HappyToster/SQL/assets/97261554/07da9260-a944-41a4-93a0-b38b05b8e473)

```иСКЛЮЧАЕТ ЗНАЧЕНИЕ```

![image](https://github.com/HappyToster/SQL/assets/97261554/9e0bbc7b-247f-4681-8931-b9b7241361ab)

#### Групповые запросы
```Количество позиций по определенной категории, сортировка по названию категории (по алфавиту)```

![image](https://github.com/HappyToster/SQL/assets/97261554/cb90afc4-38e4-4410-be39-8cb89c376e89)

```Общая стоимость и количество позиций по категориям```

![image](https://github.com/HappyToster/SQL/assets/97261554/9b828ec2-fbf9-436a-a3a6-9c31439315c2)

```Общая стоимость всех товаров из категории Электроинструмент```

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

#### Вложенные запросы
```Товар с наименьшей ценой```

![image](https://github.com/HappyToster/SQL/assets/97261554/32a60a4d-f489-43e7-a329-d97a3c8735c2)

```Вывести категории товаров (а так же название, цену и кол-во), в которых общая стоимость товаров >= 200 и количество товаров <= 10```
![image](https://github.com/HappyToster/SQL/assets/97261554/c715664c-4f4e-4bda-bbc3-65d56455e807)

```Изменить запрос для таблицы product таким образом, чтобы добавить условие: год выпуска должен быть больше 2018 года.```

![image](https://github.com/HappyToster/SQL/assets/97261554/52640000-9072-4099-a96f-74f0944e8198)

```Составить запрос для таблицы product: Показать только те товары, у которых общая стоимость меньше самой большой средней стоимости товара каждой категории.```

![image](https://github.com/HappyToster/SQL/assets/97261554/b817e77a-b19a-4d28-a958-f31dca98919a)

#### Join
```Покажи имена и адреса (включая город и страну) покупателей, которые сделали покупку 6 апреля 2022```

![image](https://github.com/HappyToster/SQL/assets/97261554/ad3bf481-0b20-4964-a414-66ad03b232ac)

_____

### Update
#### Insert
```Добавление данных в дочерние таблицы```
INSERT INTO category (id_category, category)
VALUES
('1','Tools'),
('2','Клей'),
('3','Миниатюра и диорама'),
('4','Модели и подставки'),
('5','Футляры и подставки');
	
INSERT INTO manufacturer (id_manufacturer, manufacturer)	
VALUES	
('1','MACHETE'),	
('2','Звезда'),	
('3','KAV models');
```Добавление полей в родительскую таблицу```
INSERT INTO goods (pack size, gross weight)
VALUES
('NULL','0'),
('21x7x1','15'),
('6x3x2','17'),
('16x13x3','60'),
('19x20x2','110');
);

#### Set
```Изменение данных в ячейках родительской таблицы```
USE online_store;
UPDATE goods SET id_category = "1" WHERE id_product = "1";
UPDATE goods SET id_category = "2" WHERE id_product = "2";
UPDATE goods SET id_category = "3" WHERE id_product = "3";
UPDATE goods SET id_category = "4" WHERE id_product = "4";
UPDATE goods SET id_category = "5" WHERE id_product = "5";

USE online_store;
UPDATE goods SET id_manufacturer = "1" WHERE id_product = "1";
UPDATE goods SET id_manufacturer = "2" WHERE id_product = "2";
UPDATE goods SET id_manufacturer = "3" WHERE id_product = "3";
UPDATE goods SET id_manufacturer = "2" WHERE id_product = "4";
UPDATE goods SET id_manufacturer = "1" WHERE id_product = "5";

#### Change
```Переименование полей родительской таблицы```
USE online_store;
ALTER TABLE goods
  CHANGE category id_category VARCHAR (45) NOT NULL, 
  CHANGE manufacturer id_manufacturer VARCHAR (45) NOT NULL;

_____

### Delete
