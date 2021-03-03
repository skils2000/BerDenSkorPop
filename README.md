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
![image](https://user-images.githubusercontent.com/64580259/109867128-31007c80-7c77-11eb-9243-56e5d5f52dc2.png)
### UML Diagram
![image](https://user-images.githubusercontent.com/64580259/109868699-044d6480-7c79-11eb-9c52-5b18dc85f265.png)

![image](https://user-images.githubusercontent.com/64580259/109868883-41b1f200-7c79-11eb-9592-a863c33690fc.png)



