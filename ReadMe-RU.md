# План изучения Node.js разработчика

> План изучения для становления [Node.js](https://nodejs.org/en/) разработчиком в 2019:

Ниже вы можете найти диаграмму, демонстрирующую пути, по которым вы можете пойти и библиотеки, которые вам следует изучить чтобы стать Node.js разработчиком. Я сделал эту диаграмму как совет всем, кто спрашивает меня: "Что я должен изучить, чтобы стать Node.js разработчиком?"

* Языки: [:cn: 中文](ReadMe-CN.md) | [:uk: English](/ReadMe.md) | [:pt: Português](/ReadMe-PT.md) | [:ru: Русский](/ReadMe-RU.md)

## Дисклеймер

> Цель этого плана - дать вам представление о пути. Если вы остановились на изучении, план покажет, что вам стоит изучать дальше, вместо того чтобы изучать то, что сейчас модно и в тренде. Вы должны понять, что определённые технологии лучше работают в одних случаях, чем в других, и запомнить, что модная технология не всегда означает хорошая технология

## Поставь звезду! :star:

Если вам нравится, или вы используете этот план изучения, или он помог вам в начале вашего пути разработчика, поставьте звёздочку. Спасибо!

## План изучения

![Roadmap](./Node.js-developer-roadmap-ru.png)

## Ресурсы

1. Предпосылки

   - [JavaScript](https://www.w3schools.com/js/)
   - [NPM](https://docs.npmjs.com/)
   - [Node.js](https://nodejs.org/en/docs/)
   - ES6/ES7

2. Общие навыки разработки

   - Изучение GIT, создание новых репозиториев на GitHub, делиться своим кодом с другими людьми
   - Знание протокола HTTP(S), методы запроса (GET, POST, PUT, PATCH, DELETE, OPTIONS)
   - Использование Google, [Power Searching with Google](http://www.powersearchingwithgoogle.com/)
   - Прочитайте несколько книг об алгоритмах и структурах данных

3. Веб-фреймворки

   1. [Express.js](https://expressjs.com/)
   2. [Adonis.js](https://adonisjs.com/)
   3. [Meteor.js](https://www.meteor.com/)
   4. [Nest.js](https://nestjs.com/)
   5. [Sails.js](https://sailsjs.com/)
   6. [Koa.js](https://koajs.com/)
   7. [Loopback.js](https://loopback.io/)
   8. [egg.js](https://eggjs.org/en/index.html)
   9. [midway](https://midwayjs.org/midway/en/)

4. Базы данных

   1. Реляционные базы данных
      1. [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2017)
      2. [PostgreSQL](https://www.postgresql.org/)
      3. [MariaDB](https://mariadb.org/)
      4. [MySQL](https://www.mysql.com/)
   2. Облачные базы данных
      - [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db)
      - [DynamoDB](https://aws.amazon.com/dynamodb/)
   3. Поисковые системы
      - [ElasticSearch](https://www.elastic.co/)
      - [Solr](http://lucene.apache.org/solr/)
      - [Sphinx](http://sphinxsearch.com/)
   4. NoSQL
      - [MongoDB](https://www.mongodb.com/)
      - [Redis](https://redis.io/)
      - [Apache Cassandra](http://cassandra.apache.org/)
      - [LiteDB](https://github.com/mbdavid/LiteDB)
      - [RavenDB](https://github.com/ravendb/ravendb)
      - [CouchDB](http://couchdb.apache.org/)

5. Кэширование

   1. [Node-Cache](https://www.npmjs.com/package/node-cache)
   2. Распределенный кеш
      1. [Redis](https://redis.io/)
      2. [Memcached](https://memcached.org/)
   3. [Memory Cache](https://www.npmjs.com/package/memory-cache)

6. Логирование

   1. Фреймворки для логирования
      - [Node-Loggly](https://www.loggly.com/docs/node-js-logs-2/)
      - [Winston](https://github.com/winstonjs/winston)
      - [Node-Bunyan](https://github.com/trentm/node-bunyan)
      - [Morgan](https://github.com/expressjs/morgan)
   2. Система управления журналами
      - [Sentry.io](http://sentry.io)
      - [Loggly.com](https://loggly.com)

7. Шаблонные движки
   1. [Mustache.js](https://mustache.github.io/)
   2. [Handlebars](https://handlebarsjs.com/)
   3. [EJS](https://ejs.co/)
   4. [Pug](https://pugjs.org/api/getting-started.html)
   4. [Nunjunks.js](https://mozilla.github.io/nunjucks/)
8. Связь в реальном времени

   1. [Socket.IO](https://socket.io/)


9. Типизированный Суперсет

    1. [TypeScript](https://www.typescriptlang.org/)
    2. [Flow](https://flow.org/)

10. API-клиенты

    1. REST
       - [Request](https://github.com/request/request)
       - [Node-Rest-Client](https://www.npmjs.com/package/node-rest-client)
       - [Axios](https://github.com/axios/axios)
    2. [GraphQL](https://graphql.org/)

11. Можно изучить

    - [Async.js](https://caolan.github.io/async/)
    - [PM2](http://pm2.keymetrics.io/)
    - [Commander.js](https://github.com/tj/commander.js/)
    - [Passport](http://www.passportjs.org/)
    - [Nodemailer](https://nodemailer.com/about/)
    - [Marked](https://marked.js.org/#/README.md#README.md)
    - [JSHint](https://github.com/jshint/jshint)

12. Тестирование

    1. Блок, Поведение, Интеграционное тестирование
       1. [Jest](https://jestjs.io/)
       2. [Jasmine](https://jasmine.github.io/)
       3. [Chai](https://www.chaijs.com/)
       4. [Mocha](https://mochajs.org/)
       5. [Enzyme](https://github.com/airbnb/enzyme)
       6. [Sinon](https://sinonjs.org/)
    2. E2E тестирование
       - [Selenium](https://help.crossbrowsertesting.com/selenium-testing/getting-started/javascript/)
       - [Puppeteer](https://github.com/GoogleChrome/puppeteer)

13. Планирование задач

    - [Agenda](https://github.com/agenda/agenda)
    - [Cronicle](https://github.com/jhuckaby/Cronicle)
    - [Node-Schedule](https://www.npmjs.com/package/node-schedule)
    
14. Микросервисы

    1. Message-Broker
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-javascript.html)
       - [Apache Kafka](https://www.npmjs.com/package/kafka-node)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview)
    2. Message-Bus
       - [Distribus](https://distribus.com/)
       - [BusMQ](https://github.com/capriza/node-busmq)

15. [Design-Patterns](https://www.pluralsight.com/courses/javascript-practical-design-patterns)
16. [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms/)


## Заключение

Если вы думаете, что план изучения может быть улучшен, пожалуйста, откройте PR с любыми обновлениями и отправьте любые вопросы. Так же я буду продолжать улучшать этот план, поэтому вы можете добавить этот репозиторий, чтобы вернуться к нему.

Идея от: [ASP.NET Core Developer Roadmap](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap)

## Вклад

План изучения построен с помощью [Draw.io](https://www.draw.io/). Файлы проекта могут быть найдены в файле под названием `Node.js-developer-roadmap.xml`. Чтобы изменить его откройте draw.io, кликните **Open Existing Diagram** и выберете `xml` файл с проектом. Это откроет план изучения для вас. Обновите его, загрузите и обновите изображения в файле readme и создайте PR (экспортируйте как png с 400% -ным увеличением и уменьшите его с помощью [Compressor.io](https://compressor.io/compress)).

- Отправьте PR с улучшениями
- Обсудить идеи в вопросах
- Распространите идеи

## Лицензия

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
