# Базовые знания для backend-разработчиков

## Минимальные знания

### PHP

- Типы данных, константы, суперглобальные переменные
- POST, GET и другие типы запросов
- Области видимости
- Static, Abstract классы
- Interfaces
- Traits
- ключевые слова $this, self, static
- Namespaces, Autoloading
- Магические методы
- Виды ошибок, различия (fatal, warning, notice, deprecated)
- Exceptions
- Консольные команды php (-m, --ini, -i и тд)

### Реляционные СУБД

- Синтаксис SQL
- Вложенные запросы, JOIN-ы
- Типы данных
- Ключи
- Индексы
- Транзакции
- Нормализация БД (первые 3 формы)
- SQL-инъекции
- ORM

### Паттерны программирования

- ООП
- MVC
- SOLID
- Шаблоны проектирования
  - Singleton
  - Observer
  - Factory
  - Strategy
  - Facade
  - Adapter

### Laravel

Расписать...


### Laravel Nova

- Resources

### WordPress

- Структура темы
- Структура БД
- Custom Post Types
- Advanced Custom Fields (+ ACF local json)
- Таксономии
- Мета-данные
- Хуки, фильтры
- wp-query

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
- Уметь обратиться из одного контейнера docker-compose к другому (через Compose DNS)
- Уметь работать со службами Compose: up, ps, restart, down, logs и тд

### Linux

- Уметь навигироваться по файловой системе. Вывести последние измененные файлы, найти в проекте файл с заданным вхождением, вывести логи в интерактивном режима и отгрепать их
- Уметь манипулировать файлами mv, rm, cp, scp
- Уметь просматривать процессы. Сколько процессов сейчас запущено для PHP, сколько ресурсов потребляет пользователь www, сколько свободно SWAP-памяти
- Уметь работать с символическими ярлыками, PATH, alias
- Уметь работать с ключами SSH
- Уметь администрировать PHP. Просмотр установленных расширений PHP, найти какой php.ini используется, понять какой бинарник PHP используется в терминале, а какой на вебе

## Полезные материалы

### PHP

- Официальная дока PHP https://www.php.net/manual/en/langref.php
  - Basic syntax
  - Types
  - Variables
  - Constants
  - Expressions
  - Operators
  - Control structures
  - Functions
  - Classes and objects
  - Namespaces
  - Errors
  - Exceptions
  - Attributes
  - References explained
  - Predefined variables
- Видеокурс [ENG]. Laracasts php for beginners. https://laracasts.com/series/php-for-beginners
- Видеокурс [ENG]. Laracasts php bits. https://laracasts.com/series/php-bits
- Видеокурс [ENG]. Laracasts Solid in php. https://laracasts.com/series/solid-principles-in-php
- Паттерны программирования https://refactoring.guru/design-patterns
- Книга "PHP 7. Наиболее полное руководство (3-е издание) - 2016" https://yadi.sk/i/jS1ZrskJAFmY6Q

### Laravel

- Laravel официальная документация [ENG] https://laravel.com/docs/master
  - Routing
  - Controllers
  - Requests
  - Views
  - Validation
  - Blade templates
  - Collections
  - File Storage
  - Mail
  - Events
  - Helpers
  - Migration
  - Seeding
  - Eloquent Getting Started
  - Eloquent Relationships
- Видеокурс [ENG]. Laravel Advanced https://youtu.be/_z9nzEUgro4
- Видеокурс [ENG]. Laravel from scratch http://laravelfromscratch.com
- Чат Laravel Pro https://t.me/laravel_pro Можно быстро спросить и получить ответ на вопросы по Ларе
- Книги
  - Laravel Up and running second edition https://yadi.sk/i/7ZCQEPgKmJKvgw
  - Kelt Dockins - Design Patterns in PHP and Laravel - 2017 https://yadi.sk/i/0VuK7UozffP9bQ
  - Full-Stack Vue.js 2 and Laravel 5 Bring the frontend and backend together with Vue, Vuex, and Laravel https://yadi.sk/i/MyU5aMZgC7wgpg

### Базы данных

- "Базы данных". Видеокурс от mail.ru https://youtube.com/playlist?list=PLrCZzMib1e9oOFQbuOgjKYbRUoA8zGKnj

### Laravel Nova

- Nova documentation [ENG] https://nova.laravel.com/docs
  - Раздел Resources

### WordPress ACF

- Видео на русском для быстрого старта https://youtu.be
- Дока на русском http://acfwp.ru/category/documentation/
- Официальная дока https://www.advancedcustomfields.com/resources/
