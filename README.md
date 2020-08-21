###  Стек

NodeJs (NestJs), TypeScript, TypeORM, Jest
БД: MySql/Postgresql/Mongo


###  Требования

Требуется установленный _docker_ и _docker-compose_


### Запуск

Выполняется из корневой папки

1. Запуск в режиме разработки
      _npm run dev_
2. Запуск в режиме продакшн
      _npm run dev_
3. Запуск тестов
      _npm run test_


### Создание тестовой БД

GET localhost:3000/create-test-db


### Примеры запросов

1. Список обменников
_GET :3000/shops_
2. Детали обменника
_GET :3000/shops/:id_
3. Список валют
_GET :3000/currencies_
4. Список регионов
_GET :3000/regions_
5. Список городов
_GET :3000/cities_
6. Авторизация
_POST :3000/auth/login_
7. Регистрация
_POST :3000/user/signup_
8. Отправить смс-код
_POST :3000/send-sms-code_
9. Проверить смс-код
_POST :3000/check-sms-code_
10. Сводная информация о пользователе
_GET :3000/user/dashboard_
11. Добавить новый обменник пользователю
_POST :3000/user/create-shop_
12. Изменить данные обменника
_POST :3000/user/update-shop_
13. Удалить обменник
_POST :3000/user/delete-shop_
14. Восстановить забытый пароль
_POST :3000/forgot-password_
14. Поменять телефон у пользователя
_POST :3000/user/change-phone_
15. Смена пароля
_POST :3000/user/set-password_
16. Удалить аккаунт
_POST :3000/user/delete-account_
...



...

