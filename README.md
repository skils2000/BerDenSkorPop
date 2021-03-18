# BerDenSkorPop
Список команды и роли:
1. Березов Артём Владиславович (вторая подгруппа)
2. Денисов Александр Алексеевич (вторая подгруппа)
3. Попов Сергей Евгеньевич (вторая подгруппа)
4. Скороходов Илья Сергеевич (вторая подгруппа)
 
### Функциональные требования:
1.	Транзакционные:
* Изменить цену сайта
* Изменить комплектацию сайта
* Удалить заказ
* Изменить данные клиента
* Удалить клиента
* Изменить сроки заказа

2. Аналитические:
* Высчитать стоимость заказа
* Рассчитать кол-во заказов с подключёнными базами данных
* Высчитать средную стоимость заказа

3. Оперативные:
* Вывести всех клиентов
* Вывести заказы с подключённой рекламой
* Вывести даты всех заказов
* Вывести все сайты с базовой комплектацией
* Вывести все сайты с полной комплектацией
* Вывести все сайты с начальной комплектацией

### Список сущностей:
 
1. Clients
* id - INT
* FIO - VARCHAR(n)
* Phone - INT
* Email - VARCHAR(n)

2. Orders
* id - INT
* Date - DATE
* Time - Custom

3. Advertisement
* id - INT
* Type - VARCHAR(n)
* Deadline - DATE

4. Website
* id - INT
* Price - INT
* Type - VARCHAR(n)
* Time_of_imp - VARCHAR(n)

5. Design_project
* id - INT
* Font - VARCHAR(n)
* Logo - INT
* Colour - VARCHAR(n)

6. Database
* id - INT
* Max_of_tables - INT

7. Service
* id - INT
* Filling_with_content - VARCHAR(n)
* Administration_BD - INT
* AD_rek - INT
 
### Relational Schema
![image](https://user-images.githubusercontent.com/64580259/111544319-54eab480-8785-11eb-85db-9b5e35b88f00.png)

### UML Diagram
![image](https://user-images.githubusercontent.com/64583095/111594301-f3a20000-87db-11eb-8a74-1e2fca506ef0.png)

### ER Diagram
![image](https://user-images.githubusercontent.com/64580259/111544502-9f6c3100-8785-11eb-9ff4-5c22812ac743.png)




