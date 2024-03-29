# Лабораторная работа №3

#### Тест-кейс №1

| Название 	| Описание 	|
|---	|---	|
| **Номер** 	| **1** 	|
| **Заголовок** 	| Создание экспресс-ордера 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/). Пользователь авторизован. На счете достаточно средств для создания сделки 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| Нажать на кнопку "Экспресс-ордер" 	| Отображается поле "Активы" и "Экспресс-ордер", скрывается поле "Сделки" 	|
| Выбрать 3 актива в поле "Активы" и  нажать около них на зеленую кнопку для выбора 	| Добавляется 3 актива в поле "Экспресс-ордер" во вкладку "Новый". Отображается поле для ввода суммы, общая выплата, ожидаемый доход и кнопка для подтверждения. 	|
| Ввести сумму в числовом формате 	| В поле "Сумма" отображается введенное число 	|
| Нажать на кнопку "Подтвердить" 	| В поле "Экспресс-ордер" во вкладке "Открытые" отображается информация об экспресс-ордере 	|
| Ожидание закрытия ставки 	| В поле "Экспресс-ордер" во вкладке "Закрытые" отображается информация о закрытом экспресс- ордере. При выйгрыше, к балансу добавилась выбранная сумма, при проигрыше - отнялась 	|

#### Тест-кейс №2

| **Название** 	| **Описание** 	|
|---	|---	|
| **Номер** 	| 2 	|
| **Заголовок** 	| Создание сделки 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/). Пользователь авторизован. Выбрана необходимая валюта для ставки. На счете достаточно средств для создания сделки 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| В поле для ввода суммы ввести  число для ставки в цифровом  формате 	| Отображается виртуальная клавиатура для ввода данных и сумма выигрыша/проигрыша 	|
| Нажатие на зеленую кнопку для создание сделки 	| В поле "Сделки" во вкладке "Открыто" отображается информация о сделке 	|
| Ожидание закрытия сделки 	| В поле "Сделки" во вкладке "Закрыто" отображается информация о завершенной сделке. При выйгрыше, к балансу добавилась выбранная сумма, при проигрыше - отнялась 	|

### Тест-кейс №3

| **Название** 	| **Описание** 	|
|---	|---	|
| **Номер** 	| 3 	|
| **Заголовок** 	| Создание отложенной сделки ко времени 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/)". Пользователь авторизован. На счете достаточно средств для совершения сделки 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| Нажатие на кнопку "Отложенная сделка" 	| Отображение всплывающего окна "Отложенная сделка" 	|
| Выбор актива в поле "Актив" 	| При нажатии на всплывающий список актива отображается список всех доступных активов. После выбора данные поля "Актив" изменяются на выбранный актив 	|
| Ввод времени открытия сделки в поле "Время открытия" в формате ГГГГ-ДД-ММ чч:мм:сс 	| Вводимые данные отображаются в поле "Время открытия" 	|
| Ввод выплаты в поле "Выплаты" в числовом формате 	| Вводимые данные отображаются в поле "Выплаты" 	|
| Выбор периода в поле "Период" 	| При нажатии на всплывающий список периода отображается список всех доступных периодов. После выбора данные поля "Период" изменяются на выбранный период. 	|
| Ввод суммы в поле "Сумма" 	| Вводимые данные отображаются в поле "Сумма" 	|
| Нажатие на зеленую/красную кнопку для создания сделки 	| Отображается уведомление в правом нижнем углу об успешном создании сделки. Вкладка "Активные" во всплывающем окне обновляется и к счетчику добавляется одна сделка 	|

### Тест-кейс №4

| **Название** 	| **Описание** 	|
|---	|---	|
| **Номер** 	| 4 	|
| **Заголовок** 	| Добавление актива в избранные 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/). Пользователь авторизован 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| Нажать на выбранный актив 	| Открывается список со всеми активами 	|
| Нажать на звездочку рядом с выбранным активом 	| Звездочка залилась оранжевым цветом. Появилась вкладка с выбранным активом 	|

### Тест-кейс №5

| **Название** 	| **Описание** 	|
|---	|---	|
| **Номер** 	| 5 	|
| **Заголовок** 	| Изменение имени пользователя 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/). Пользователь авторизован 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| Нажать на кнопку "Профиль" 	| Открытие всплывающего окна "Профиль"  	|
| Нажать на кнопку "Профиль" во всплывающем окне 	| Открытие [страницы профиля](https://pocketoption.com/ru/cabinet/profile/) 	|
| Нажатие на поле "Имя" 	| Отображение элементов для сохранения/отката изменений, кнопка для удаления введенных данных 	|
| Ввод нового имени пользователя одним словом в строчном формате на русском языке 	| Введенные данные отображаются в поле ввода 	|
| Нажатие на галочку для сохранения изменений 	| Отображение уведомления об успешном изменении имени пользователя. В поле для ввода отображается новое имя пользователя, введенное транслитом. 	|

### Тест-кейс №6

| **Название** 	| **Описание** 	|
|---	|---	|
| **Номер** 	| 6 	|
| **Заголовок** 	| Изменение внешнего вида графика на линию 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/). Пользователь авторизован 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| Нажатие на кнопку "Типы графика" с изображением свечей в левом верхнем углу 	| Отображение всплывающего меню "Типы графика" 	|
| Нажатие на кнопку "Линия" 	| График отображается в виде линии 	|

### Тест-кейс №7

| **Название** 	| **Описание** 	|
|---	|---	|
| **Номер** 	| 7 	|
| **Заголовок** 	| Построении линий Фибоначчи на графике 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/). Пользователь авторизован 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| Нажатие на кнопку "Построения" в левом верхнем углу 	| Открытие всплывающего меню с возможными построениями 	|
| Нажатие на кнопку "Линии Фибоначчи" во всплывающем меню 	| Построение линий Фибоначчи на графике 	|

### Тест-кейс №8

| **Название** 	| **Описание** 	|
|---	|---	|
| **Номер** 	| 8 	|
| **Заголовок** 	| Создание мультиграфика 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/). Пользователь авторизован 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| Нажатие на кнопку "Мультиграфик" в левом верхнем углу 	| Отображение всплывающего меню с возможными комбинациями мультиграфика 	|
| Нажатие кнопку с конфигурацией с двумя графиками, у которых ось симметрии расположена на оси Y 	| Отображение двух окон для ставок 	|

### Тест-кейс №9

| **Название** 	| **Описание** 	|
|---	|---	|
| **Номер** 	| 9 	|
| **Заголовок** 	| Отправка сообщения в общем чате 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/). Пользователь авторизован 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| Нажатие на кнопку "Чат" в левой середине окна 	| Отображение поля "Чаты" в левой части окна 	|
| Нажатие на кнопку "Общий чат" в поле "Чат" 	| Открытие общего чата в поле "Чат" 	|
| Ввод текста в поле "Текст сообщения" 	| Вводимые данные отображены во вводимом поле 	|
| Нажатие на кнопку "Enter" на клавиатуре 	| Введенный текст отображается в чате 	|

### Тест-кейс №10

| **Название** 	| **Описание** 	|
|---	|---	|
| **Номер** 	| 10 	|
| **Заголовок** 	| Одновременная сделка на повышение и понижение 	|
| **Предусловие** 	| Открыта страница ["Быстрая торговля демо-счет"](https://pocketoption.com/ru/cabinet/demo-quick-high-low/). Пользователь авторизован. Выбран необходимый актив. На счете достаточно средств для создания сделки 	|
| **Шаг** 	| **Ожидаемый результат** 	|
| В поле для ввода суммы ввести число для ставки в цифровом формате 	| Отображается виртуальная клавиатура для ввода данных и сумма выигрыша/проигрыша 	|
| Нажатие на зеленую кнопку для создание сделки 	| В поле "Сделки" во вкладке "Открыто" отображается информация о сделке 	|
| В поле для ввода суммы ввести число для ставки в цифровом формате 	| Отображается виртуальная клавиатура для ввода данных и сумма выигрыша/проигрыша 	|
| Нажатие на красную кнопку для создание сделки 	| В поле "Сделки" во вкладке "Открыто" отображается информация о сделке 	|
| Ожидание закрытия сделки 	| В поле "Сделки" во вкладке "Закрыто" отображается информация о завершенных сделках. Баланс не изменился. 	|