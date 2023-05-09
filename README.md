# SQL
Привет!) Здесь о том, как я изучала запросы SQL и работала в MySQL Workbench и Shell в рамках интенсива от "Школы седого тестировщика".

## Оглавление
1. [Create](#create)
2. [Read](#create)
    1. [Простые селекты](#простые-селекты)
4. [Update](#update)
5. [Delete](#delete)

_____

### Create
CREATE TABLE название таблицы (
название столбца1 INT PRIMARY KEY AUTO_INCREMENT,
название столбца2 тип данных,
название столбца3 тип данных
);

INSERT INTO название таблицы (столбец1, столбец2)
VALUES
 (значение 1.1, значение 1.2)
);

UPDATE таблица SET столбец = "значение" WHERE (и добавить условие, например id = 4, чтобы обойти защиту)
_____

### Read
#### Простые селекты
>Показать список баз данных

![image](https://github.com/HappyToster/SQL/assets/97261554/350da904-e02c-475d-9c81-3c0da632fe93)

>Показать список таблиц в базе

![image](https://github.com/HappyToster/SQL/assets/97261554/7eb24c5a-d74f-4870-ac65-95ce79dfc945)

>Выборка всех данных из таблицы

![image](https://github.com/HappyToster/SQL/assets/97261554/bb8e0513-88d1-4f98-816b-e2d5ffeaca30)

>Выборка определенных столбцов из таблицы

![image](https://github.com/HappyToster/SQL/assets/97261554/c78a962a-43f3-4cae-9f23-4cc90f73dc98)

>Выборка  по условию&&&&&&&&&

![image](https://github.com/HappyToster/SQL/assets/97261554/4136d2ca-aa09-4914-b429-7fbca3bbfd3f)

>Поменять название столбца при выводе

![image](https://github.com/HappyToster/SQL/assets/97261554/3057a83b-df78-428b-97cf-13edd3b377f3)

>ДОБАВИТЬ ОПЕРАЦИЮ

![image](https://github.com/HappyToster/SQL/assets/97261554/679a729e-7d31-4470-9a29-e176777cdc74)

>ЦЕНА ВЫШЕ 500

![image](https://github.com/HappyToster/SQL/assets/97261554/536188fd-e487-40ca-9333-dc9d22d18ed9)

>БАЛ

![image](https://github.com/HappyToster/SQL/assets/97261554/1d5d1494-c299-4cf4-b4ce-86e9163d6bfb)

>блабла

![image](https://github.com/HappyToster/SQL/assets/97261554/0711a9bc-0edf-4d9e-9219-c2174c8c3d1d)

>GGG

![image](https://github.com/HappyToster/SQL/assets/97261554/5010710a-9f91-441d-ba7e-3f0aec565a31)

>LLL

![image](https://github.com/HappyToster/SQL/assets/97261554/01ea2703-fab2-4ae8-af16-f2068b5b7c4c)

>ВЫВОДИТ ВКЛЮЧИТЕЛЬНО

![image](https://github.com/HappyToster/SQL/assets/97261554/a763736c-02db-4d06-9052-4311e1ff7223)
										
>НЕ ТАКОЙ И НЕ ТАКОЙ. ОТСЕКАЕТ ЗНАЧЕНИЯ В СКОБКАХ

![image](https://github.com/HappyToster/SQL/assets/97261554/7b52e790-fcc1-4233-828d-088c06014db3)
							
>ПОЯВЯТСЯ ТОЛЬКО ЗНАЧ В СКОБКАХ

![image](https://github.com/HappyToster/SQL/assets/97261554/e403382c-dae1-4ae9-a92e-e7f8d5ce07f4)

>По возрастанию

![image](https://github.com/HappyToster/SQL/assets/97261554/8ef487eb-549c-4d7f-928c-0f50c78ed66e)

>ПО УБЫВАНИЮ

![image](https://github.com/HappyToster/SQL/assets/97261554/07da9260-a944-41a4-93a0-b38b05b8e473)

>иСКЛЮЧАЕТ ЗНАЧЕНИЕ

![image](https://github.com/HappyToster/SQL/assets/97261554/9e0bbc7b-247f-4681-8931-b9b7241361ab)
	
_____

### Update

UPDATE ТАБЛ SET СТОЛБ = "ЗНАЧ" WHERE ID > 0; ТАК ДЕЛАЕМ, ЧТОБ ОБОЙТИ БЕЗОПАСНЫЙ РЕЖИМ. ИЛИ МОЖНО КОНКРЕТНУЮ СТРОКУ УКАЗАТЬ, НАПР ID = 4										

_____

### Delete
