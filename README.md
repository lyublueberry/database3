# database3
Запросы к базе данных. Оператор SELECT. Часть 3
Тема: “Объединение таблиц”.
1. Напишите запрос, который бы вывел агентов, живущих в одном и том же городе, упорядочив по городам.

2. Тема: “Вставка одного запроса внутрь другого”.
Напишите запрос, который бы использовал подзапрос для получения всех заказов для заказчика с именем «Три кота». Предположим, что вы не знаете номера этого заказчика, указываемого в поле ID_Заказчик.

3. Тема: “Подзапросы”.
Напишите команду SELECT, использующую подзапрос,  и которая выберет имена и номера всех заказчиков с максимальными для их городов рейтингами.

4. Тема: “Использование оператора EXISTS”.
Напишите запрос, который бы использовал оператор EXISTS для извлечения всех агентов, которые имеют заказчиков с рейтингом, равным 60.

5. Тема: “Использование операторов ANY, ALL, SOME”.
Напишите запрос, который бы выбирал всех заказчиков, чьи рейтинги равны или больше чем любой (ANY) рейтинг заказчика «Мясокомбинат».

6 Тема: “Использование предложения  UNION”.

Создайте объединение из двух запросов, которое показало бы имена, города и рейтинги всех заказчиков. Те из них, которые имеют поле rating=60 и более, должны, кроме того, иметь слова - "Высокий Рейтинг", а остальные должны иметь слова " Низкий Рейтинг ".
