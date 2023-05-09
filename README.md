# SQL
Привет!) Здесь о том, как я изучала запросы SQL и работала в MySQL Workbench и Shell в рамках интенсива от "Школы седого тестировщика".

## Оглавление
1. Create
2. Read
3. Update
4. Delete

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

SELECT * FROM ТАБЛ WHERE СТОЛБ BETWEEN 2 AND 3 - ВЫВОДИТ ВКЛЮЧИТЕЛЬНО										
										
SELECT * FROM ТАБЛ WHERE СТОЛБ NOT IN ('ЗНАЧ1', 'ЗНАЧ2'...) - НЕ ТАКОЙ И НЕ ТАКОЙ. ОТСЕКАЕТ ЗНАЧЕНИЯ В СКОБКАХ										
										
SELECT * FROM ТАБЛ WHERE СТОЛБ IN ('ЗНАЧ1', 'ЗНАЧ2'...) - ПОЯВЯТСЯ ТОЛЬКО ЗНАЧ В СКОБКАХ										
										
SELECT * FROM ТАБЛ ORDER BY СТОЛБ ПО КОТ ДЕЛАЕМ УПОР-НИЕ ASC ИЛИ DESC										
										
_____

### Update

UPDATE ТАБЛ SET СТОЛБ = "ЗНАЧ" WHERE ID > 0; ТАК ДЕЛАЕМ, ЧТОБ ОБОЙТИ БЕЗОПАСНЫЙ РЕЖИМ. ИЛИ МОЖНО КОНКРЕТНУЮ СТРОКУ УКАЗАТЬ, НАПР ID = 4										

_____

### Delete
