npm server - запуск сервера \
npm css - style watch \
npm start - запуск реакт

Текущие задачи
* fg центральной диаграммы
* Сумма расходов по столбцу год, месяц
* Вывод доп диаграм месяца
* Переделать подборку цветов пирожка

Задачи
* Изменить "маршрутизацию" серверных запросов
* Комменты !!!
* Валидация ячеек
* Пустая страница, создание новой таблицы на основе текущего дня при добавлении новой строки расходов
* Досмотреть маршрутизацию с "Использование switch"

Второстепенные задачи
* Загитигнорить .idea, build
* Архив, статистика, 
* Автоматическое добавление текущего дня в таблицу
* Error при вооде профита
* Туча варнингов)
* Убрать finalSum из TableItem
* Оффлайн
* Вынести не сервер
* Нормальный дизайн
* Тесты
* Redux 
* авторизация getIp в корне + 
* в статистике пирожок статей не сбросить обратно до города

Заметки
* Архив будет работать аналогично главной, только в отдельном json. + Переносить finalSum года
* При добавлении нового scss файла - надо вбить его руками, пока так
* Снести clearTable



\
\
\
\
\
Недоработки с которыми пока приходится мириться
1. Повсеместное map'ирование таблицы
2. tableItem в т.ч. для месяца и профита
3. addDay return
4. Добавление css файлов вручную
5. Столбец > 98