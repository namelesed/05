# XPath'ы страниц "1. Выбор полиса" и "2. Оформление" сайта [СберСтрахования](https://online.sber.insure/store/propertyins/): 

## Кнопки:

|Номер|Кнопка|Xpath|  
|:-|:--|:--------|
|1|"Квартира"|//*[contains(text(),'Квартира')]/parent::button|
|2|"Дом"|//*[contains(text(),'Дом')]/parent::button|
|3|Сдается в аренду "Да"|//div[text()='Сдается в аренду']//following::button[1]|
|4|Сдается в аренду "Нет"|//div[text()='Сдается в аренду']//following::button[2]|
|5|Расположена на первом этаже "Да"|//div[contains(text(),'этаже')]//following::button[1]|
|6|Расположена на первом этаже "Нет"|//div[contains(text(),'этаже')]//following::button[2]|
|7|Установлена охранная сигнализация "Да"|//div[contains(text(),'сигнализация')]//following::button[1]|
|8|Установлена охранная сигнализация "Нет"|//div[contains(text(),'сигнализация')]//following::button[2]|
|9|"Применить"|//div[@class='reg-button']//button|
|10|"Оформить" на 1 стр|//div[@class="form-actions"]/button|
|11|"Заполнить по Сбер ID"|//span[text()=' Заполнить по Сбер ID ']/ancestor::button|
|12|"Мужской"|//span[text()='Мужской']/ancestor::button|
|13|"Женский"|//span[text()='Женский']/ancestor::button|
|14|"Вернуться"|//span[text()='Вернуться']/ancestor::button|
|15|"Оформить" на 2 стр|//span[text()='Оформить']/ancestor::button|

## Поля для ввода текста: 

|Номер|Поле ввода|Xpath|  
|:-|:--|:--------|
|1|Регион проживания|//input[@formcontrolname='registrationRegion']|
|2|Промокод|//input[@formcontrolname='promoCode']|
|3|Фамилия|//input[@data-placeholder='Фамилия']|
|4|Имя|//input[@data-placeholder='Имя']|
|5|Отчество|//input[@data-placeholder='Отчество']|
|6|Серия|//input[@formcontrolname='docSeries']|
|7|Номер|//input[@data-placeholder='Номер']|
|8|Кем выдан|//textarea|
|9|Код подразделения|//input[@data-placeholder='Код подразделения']|
|10|Регион|//input[@data-placeholder='Регион']|
|11|Город или населенный пункт|//input[@formcontrolname='registrationCity']|
|12|Улица|//input[@data-placeholder='Улица']|
|13|Дом, литера, корпус, строение|//input[@formcontrolname='registrationHouse']|
|14|Квартира|//input[@data-placeholder='Квартира']|
|15|Телефон|//input[@formcontrolname='contactPhone']|
|16|Электронная почта|//input[@type="email"][@data-placeholder='Электронная почта *']|
|17|Повтор электронной почты|//input[@type="email"][@data-placeholder='Повтор электронной почты *']| 

## Другие элементы:

|Номер| Элемент| Xpath |  
|:-|:-----|:----------|
|1|Логотип "СБЕР СТРАХОВАНИЕ"|//div[@class='sber-logo']|
|2|Датапикер "Срок действия страхования"|//mat-datepicker-toggle|
|3|Датапикер "Дата рождения"|//mat-datepicker[@class='ng-tns-c61-6']|
|4|Датапикер "Дата выдачи"|//mat-datepicker[@class='ng-tns-c61-9']|
|5|Слайдер в блоке выбора суммы|//div[@class='mat-slider-wrapper']|
|6|Чекбокс "Отчество отсутствует"|//*[text()='Отчество отсутствует']//ancestor::mat-checkbox|
|7|Чекбокс "Улица отсутствует"|//*[text()='Улица отсутствует']//ancestor::mat-checkbox|
|8|Хедер "Что будет застраховано?"|//h4[@class='block-header']|
|9|Текстовый блок "Мебель, техника и ваши вещи"|//div[text()=' Мебель, техника и ваши вещи ']|
|10|Текстовый блок "Падение летательных аппаратов и их частей"|//div[text()='Падение летательных аппаратов и их частей']|
|11|Левая колонка под хедером "Страховая защита"|//div[text()='Чрезвычайная ситуация']/ancestor::ul|
|12|Правая колонка под хедером "Страховая защита"|//div[text()='Стихийные бедствия']/ancestor::ul|


