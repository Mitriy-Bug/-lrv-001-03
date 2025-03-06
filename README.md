# Задание 3. Установка Laravel

## список composer-пакетов
[bin](example-app%2Fvendor%2Fbin)
[brick](example-app%2Fvendor%2Fbrick)
[carbonphp](example-app%2Fvendor%2Fcarbonphp)
[composer](example-app%2Fvendor%2Fcomposer)
[dflydev](example-app%2Fvendor%2Fdflydev)
[doctrine](example-app%2Fvendor%2Fdoctrine)
[dragonmantank](example-app%2Fvendor%2Fdragonmantank)
[egulias](example-app%2Fvendor%2Fegulias)
[fakerphp](example-app%2Fvendor%2Ffakerphp)
[filp](example-app%2Fvendor%2Ffilp)
[fruitcake](example-app%2Fvendor%2Ffruitcake)
[graham-campbell](example-app%2Fvendor%2Fgraham-campbell)
[guzzlehttp](example-app%2Fvendor%2Fguzzlehttp)
[hamcrest](example-app%2Fvendor%2Fhamcrest)
[laravel](example-app%2Fvendor%2Flaravel)
[league](example-app%2Fvendor%2Fleague)
[mockery](example-app%2Fvendor%2Fmockery)
[monolog](example-app%2Fvendor%2Fmonolog)
[myclabs](example-app%2Fvendor%2Fmyclabs)
[nesbot](example-app%2Fvendor%2Fnesbot)
[nette](example-app%2Fvendor%2Fnette)
[nikic](example-app%2Fvendor%2Fnikic)
[nunomaduro](example-app%2Fvendor%2Fnunomaduro)
[phar-io](example-app%2Fvendor%2Fphar-io)
[phpoption](example-app%2Fvendor%2Fphpoption)
[phpunit](example-app%2Fvendor%2Fphpunit)
[psr](example-app%2Fvendor%2Fpsr)
[psy](example-app%2Fvendor%2Fpsy)
[ralouphie](example-app%2Fvendor%2Fralouphie)
[ramsey](example-app%2Fvendor%2Framsey)
[sebastian](example-app%2Fvendor%2Fsebastian)
[spatie](example-app%2Fvendor%2Fspatie)
[symfony](example-app%2Fvendor%2Fsymfony)
[theseer](example-app%2Fvendor%2Ftheseer)
[tijsverkoyen](example-app%2Fvendor%2Ftijsverkoyen)
[vlucas](example-app%2Fvendor%2Fvlucas)
[voku](example-app%2Fvendor%2Fvoku)
[webmozart](example-app%2Fvendor%2Fwebmozart)

## директория config
1. app.php

   Основные настройки приложения :
   Часовой пояс (timezone), локаль (locale).
   Ключ приложения (key) для шифрования.
   Режим отладки (debug).
   Псевдонимы классов (aliases) и провайдеры сервисов (providers).



2. auth.php

   Аутентификация и авторизация :
   Настройки гвардов (guards) и провайдеров (providers) для пользователей.
   Сброс паролей и подтверждение email.



3. broadcasting.php

   Настройки вещания событий (WebSockets) :
   Конфигурация драйверов (Pusher, Redis, Log).



4. cache.php

   Кэширование :
   Драйверы кэша (Redis, Memcached, File и др.).
   Время жизни кэша по умолчанию.



5. cors.php

   CORS (Cross-Origin Resource Sharing) :
   Разрешенные домены, заголовки, методы HTTP.



6. database.php

   Подключение к базам данных :
   Настройки соединений (MySQL, PostgreSQL, SQLite).
   Конфигурация миграций и редисайна.



7. filesystems.php

   Хранение файлов :
   Диски (локальные, облачные: AWS S3, FTP).
   Публичные и приватные директории.



8. hashing.php

   Хеширование паролей :
   Алгоритмы (Bcrypt, Argon2) и настройки.



9. logging.php

   Логирование :
   Каналы логирования (single, daily, slack, syslog).
   Уровни логов (debug, info, error и т.д.).



10. mail.php

    Отправка email :
    Драйверы (SMTP, Mailgun, Sendmail).
    Настройки шаблонов и очередей.



11. queue.php

    Очереди задач :
    Драйверы (Redis, Database, SQS).
    Настройки задержек и повторных попыток.



12. sanctum.php

    API-аутентификация (Sanctum) :
    Токены, срок действия, middleware.



13. services.php

    Внешние сервисы :
    API-ключи (Google, Facebook, Stripe и др.).



14. session.php

    Сессии :
    Драйверы (file, cookie, database).
    Время жизни сессии и домен.



15. view.php

    Шаблоны Blade :
    Кэширование представлений, пути к шаблонам.



### В какой директории хранятся основные файлы (классы) с бизнес-логикой приложения? 
app