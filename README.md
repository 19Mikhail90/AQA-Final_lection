# AQA-Final_lection
**План тестирования формы записи на обучение профессии "Тестировщик ПО"**

***Перечень автоматизируемых сценариев***
1. Выбрать на главной страници "Каталог курсов", перейти в раздел "Программирование", найти и выбрать курс "Тестировщик ПО". Нажать кнопку "Записаться" и автоматически перенестись к форме заявки или прокрутить до низа страницы. 
2. Выбрать на главной странице раздел "НЕО для начинающих", найти и выбрать курс "Тестировщик ПО". Нажать кнопку "Записаться" и автоматически перенестись к форме заявки или прокрутить до низа страницы. 
3. Выбрать на главной странице "Каталог курсов", выбрать раздел "Полный каталог", найти и выбрать курс "Тестировщик ПО". Нажать кнопку "Записаться" и автоматически перенестись к форме заявки или прокрутить до низа страницы. 
4. Выбрать на главной странице в блоке "Изучайте актуальные темы", раздел "Программирование", найти и выбрать курс "Тестировщик ПО". Нажать кнопку "Записаться" и автоматически перенестись к форме заявки или прокрутить до низа страницы. 
5. Нажать "Выбрать курс" на главной странице в блоке "Раскройте свои сильные стороны", найти и выбрать курс "Тестировщик ПО". Нажать кнопку "Записаться" и автоматически перенестись к форме заявки или прокрутить до низа страницы. 
6. Выбрать "Каталог курсов" в футере главной страницы, найти и выбрать курс "Тестировщик ПО". Нажать кнопку "Записаться" и автоматически перенестись к форме заявки или прокрутить до низа страницы. 
7. Неавторизированный пользователь заполняет заявку валидными данными. Обязательные поля для заполнения: имя, телефон, email. 
8. Авторизированный пользователь заполняет заявку валидными данными. Обязательные поля для заполнения: имя, телефон.
9. Неавторизированный пользователь отправляет форму с пустыми полями.
10.Авторизированный пользователь отправляет форму с пустыми полями.
11. Неавторизированный пользователь отправляет форму с невалидным именем.
12. Авторизированный пользователь отправляет форму с невалидным именем.
13. Неавторизированный пользователь отправляет форму с невалидным телефоном.
14. Авторизированный пользователь отправляет форму с невалидным телефоном.
15. Неавторизированный пользователь отправляет форму с невалидным email.
16. Авторизированный пользователь отправляет форму с невалидным email.
17. Неавторизированный пользователь отправляет форму с валидными данными два раза подряд.
18. Авторизированный пользователь отправляет форму с валидными данными два раза подряд.



***Перечень используемых инструментов с обоснованием выбора***
* JAVA - в качестве удобного языка для написания тестов с множеством возможностей.
* Git - для сохранения всех версий тестов.
* GitHub - для удобства удаленного хранения кода.
* Gradle - быстрота сборки и простота в настройки компонентов.
* Selenide - простая настройка и широкий выбор локаторов
* Allure - детальный и понятные отчеты для автотестов.
* JUnit - упростит процесс модульного тестирования.
* Docker - для разворачивания окружения например, для тестировани на другой ОС.

***Перечень необходимых разрешений/данных/доступов***
* Разрешение на автоматизированное тестирование сайта
* Тестовый аккаунт.
* Тестовая почта.
* Доступ к БД заявок на обучение.
* Доступ к API


***Перечень и описание возможных рисков при автоматизации***

* Сложность при поиске локаторов.
* Возможный выход сайта работоспособного состояния.
* Частые изменения структуры страницы в ходе выполнения проекта.
* Отсутствие опытных специалистов в штате компании или на рынке труда.

***Перечень необходимых специалистов для автоматизации***

* Автоматизаторы - 1 человек.

***Интервальная оценка с учётом рисков (в часах)***

* На разработку тестов и их запуск - 12 часов + 3 часа на преодоления наступивших рисков.




