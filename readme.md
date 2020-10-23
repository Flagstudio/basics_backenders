# Базовые знания для backend-разработчиков

## Минимальные знания

### Laravel

- Laravel documentation [ENG] https://laravel.com/docs/master . Необходимые для работы разделы:
  - [Routing](https://laravel.com/docs/master/routing)
  - [Controllers](https://laravel.com/docs/master/controllers)
  - [Requests](https://laravel.com/docs/master/requests)
  - [Views](https://laravel.com/docs/master/views)
  - [Validation](https://laravel.com/docs/master/validation)
  - [Blade templates](https://laravel.com/docs/master/blade)
  - [Collections](https://laravel.com/docs/master/collections)
  - [File Storage](https://laravel.com/docs/master/filesystem)
  - [Mail](https://laravel.com/docs/master/mail)
  - [Events](https://laravel.com/docs/master/events)
  - [Helpers](https://laravel.com/docs/master/helpers)
  - [Migration](https://laravel.com/docs/master/migrations)
  - [Seeding](https://laravel.com/docs/master/seeding)
  - [Eloquent Getting Started](https://laravel.com/docs/master/eloquent)
  - [Eloquent Relationships](https://laravel.com/docs/master/eloquent-relationships)

### Laravel Nova

- Nova documentation [ENG] https://nova.laravel.com/docs
  - Раздел Resources

### Git

  - Настройка игнорирования
  - Знать что такое ветка и тэг и зачем они нужны. Знать GitFlow
  - Умение коммитить. Сквошить коммиты, делить, амендить
  - Не коммитить лишнего: логи, большие файлы, секреты, локальные настройки, директории пакетов (node_modules, vendor) и так далее
  - Умение осматривать репозиторий. Осматривать и сравнивать ветки, коммиты, тэги. Сравнить две ветки по длине, два коммита по коду.
  - Уметь переписывать историю, знать когда это можно делать а когда нет. Интерактивный ребейз, все флаги команды git reset.
  - Уметь не только merge, но и rebase, cherry-pick и revert. Уметь решать конфликты.
  - Знать разницу между pull и fetch
  - Уметь работать с несколькими привязанными репозиториями
  - Умение работать со связанными ветками. Просматривать, связывать.
  - Понимание, что такое master и origin/master.

### Docker

- Понимать что такое image и что такое container
- Уметь push pull обрразов. Смеотреть их историю, коммитить.
- Знать синтаксис Dockerfile и контекст
- Уметь работать с контейнерами: ps, inspect, log, bash (вход в конйтенер)
- Знать что такое volume и как его можно прокинуть в контейнер
- Знать как прокинуть порты в контейнер
- Знать синтаксис Docker Compose и понимать что это такое. ПОнимать что такое службы Compose
- Уметь работать со службами Compose: up, ps, restart, down, logs и тд

### Linux

- Уметь навигироваться по файловой системе. Вывести последние измененные файлы, найти в проекте файл с заданным вхождением, вывести логи в интерактивном режима и отгрепать их
- Уметь манипулировать файлами mv, rm, cp, scp
- Уметь просматривать процессы. Сколько процессов сейчас запущено для PHP, сколько ресурсов потребляет пользователь www, сколько свободно SWAP-памяти
- Уметь работать с символическими ярлыками, PATH, alias
- Уметь работать с ключами SSH
- Уметь администрировать PHP. Просмотр установленных расширений PHP, найти какой php.ini используется, понять какой бинарник PHP используется в терминале, а какой на вебе

## Полезные материалы

### Laravel

- Видео по продвинутым фичам laravel - Laravel Advanced https://youtu.be/_z9nzEUgro4
- Laravel from scratch. Видеокурс на Laracasts [ENG] http://laravelfromscratch.com
- Канал в Telegram Laravel News https://t.me/laravelnews
- Чат Laravel Pro https://t.me/laravel_pro Можно быстро спросить и получить ответ на вопросы по Ларе
- Nova documentation [ENG] https://nova.laravel.com/docs Все разделы.

### PHP

- Laracasts php for beginners. https://laracasts.com/series/php-for-beginners
- Laracasts php bits. https://laracasts.com/series/php-bits
- Laracasts Solid in php. https://laracasts.com/series/solid-principles-in-php


### Базы данных

- "Базы данных". Видеокурс от mail.ru https://youtu.be/SfYaAQ9-RnE
