# BerDenSkorPop
Список команды и роли:
1. Березов Артём Владиславович (вторая подгруппа)
2. Денисов Александр Алексеевич (вторая подгруппа)
3. Попов Сергей Евгеньевич (вторая подгруппа)
4. Скороходов Илья Сергеевич (вторая подгруппа)

    Предметная область данного проекта - это создание, продажа и поддержка веб-сайтов. В начале, проект будет нацелен на создание простых сайтов, таких как лендинг пейджи, фанфики и блоги. Далее, с увеличением нашего опыта и, возможно, персонала, планируется увеличение сложности веб-страниц и сайтов.
    
    На данный момент мы можем предложить клиенту оформить дизайнерский проект, подключить БД.   
    У нас имеется 2 готовых пакета Базовый и Продвинутый. А так же пакет Премиум, но он сейчас находится на доработке.
    Пожеланию клиента мы можем сами заняться выгрузкой и поддержкой сайта, за доп. плату, конечно же.
    
    Все заказы клиент может сделать через наш сайт. После получения сообщения мы связываемся с клиентом для обговорення дедлайнов и его пожеланий.
 
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




