Краткое содержание глав
==
В книге каждая глава посвящена отдельному тактическому строительному блоку предметно-ориентированного проектирования. 
Он также включает введение в предметно-ориентированное проектирование, информацию о том, 
как интегрировать различные ограниченные контексты или приложения, а также несколько интересных приложений.

### Глава 1. Начало работы с предметно-ориентированным проектированием
Что такое доменно-ориентированное проектирование? Какую роль он играет в сложных системах? 
Это достойно? Какие основные понятия должен знать разработчик, приступая к работе?

### Глава 2: Архитектурные стили
Ограниченные контексты могут быть реализованы разными способами и с использованием разных подходов. 
Однако два стиля становятся все более популярными: гексагональная архитектура и CQRS + ES.
В этой главе мы рассмотрим эти два основных архитектурных стиля, 
поймем их основные сильные стороны и узнаем, когда их использовать.

### Глава 3: Объекты-значения
Объекты значений — это основные элементы расширенного моделирования. 
Мы узнаем, каковы их свойства и что делает их такими важными. 
Мы проверим, как сохранить их с помощью Doctrine и пользовательских ORM. 
Мы покажем, как правильно их проверять и тестировать. 
И, наконец, мы посмотрим, как выглядит тестовый пример проверки неизменяемости.

### Глава 4: Сущности
Сущности — это строительные блоки доменно-ориентированного проектирования, 
которые однозначно идентифицируются и изменяются. Мы увидим, как их создавать и проверять, 
а также как правильно отображать их с помощью специального ORM и Doctrine. 
Мы также выясним, являются ли аннотации лучшим подходом к отображению для сущностей, 
и рассмотрим различные стратегии создания идентификаторов.

### Глава 5: Доменные службы
В этой главе вы узнаете, что такое доменная служба и когда ее использовать. 
Мы рассмотрим, что такое анемичные доменные модели и богатые доменные модели. 
Наконец, мы займемся проблемами инфраструктуры при написании доменных служб.

### Глава 6: События домена
События предметной области — отличный механизм инверсии управления (IoC). 
В доменно-ориентированном проектировании они важны для асинхронной связи с различными ограниченными контекстами, 
повышения производительности вашего приложения за счет конечной согласованности 
и отделения вашего приложения от его инфраструктуры.

### Глава 7: Модули
При таком количестве тактических строительных блоков немного сложно понять, где их разместить в коде, 
особенно если вы имеете дело с такой структурой, как Symfony. 
Мы рассмотрим, как пространства имен PHP можно использовать для реализации модулей. 
Мы также проверим различные иерархии папок для организации кода модели предметной области, 
кода приложения и кода инфраструктуры.

### Глава 8: Агрегаты
Агрегаты, вероятно, являются самой сложной частью тактического доменно-ориентированного проектирования. 
Мы рассмотрим ключевые концепции при работе с ними и узнаем, как их проектировать. 
Мы также предложим практический сценарий, в котором два агрегата становятся одним при добавлении бизнес-правила, 
и продемонстрируем, как необходимо выполнить рефакторинг остальных объектов.

### Глава 9: Фабрики
Фабричные методы и объекты помогают нам сохранять бизнес-инварианты,
поэтому они так важны в доменно-ориентированном проектировании. 
Здесь мы также проверим связь между фабриками и агрегатами.

### Глава 10: Репозитории
Репозитории являются ключевыми для извлечения и добавления сущностей и агрегатов в коллекции.
Мы рассмотрим различные типы репозиториев и узнаем, как их реализовать с помощью Doctrine, пользовательских ORM и Redis.

### Глава 11: Приложение
Приложение — это тонкий слой, который соединяет клиентов извне с вашим доменом. 
В этой главе мы покажем вам, как писать службы приложений так, чтобы их было легко тестировать 
и чтобы они были экономичными. Мы также рассмотрим, как подготовить объекты запроса, 
определить зависимости и вернуть результаты.

### Глава 12: Интеграция ограниченных контекстов
Мы рассмотрим различные тактические подходы к передаче ограниченных контекстов и увидим реальные реализации. 
REST — это наше предложение по синхронному общению, 
а обмен сообщениями с помощью RabbitMQ — это наше предложение по асинхронному общению.

### Код и примеры
Авторы создали на GitHub организацию под названием [Domain-Driven Design в PHP](https://github.com/dddshelf/), 
где доступны все примеры кода из этой книги, дополнительные фрагменты и некоторые полные примеры проектов. 
Например, вы можете найти [«Last Wishes»](https://github.com/dddshelf/last-wishes), 
простое приложение в стиле предметно-ориентированного проектирования, 
демонстрирующее различные примеры, описанные в этой книге. 
Кроме того, вы найдете наш [«Блог CQRS»](https://github.com/dddshelf/blog-cqrs), 
а также [«Gamify»](https://github.com/dddshelf/last-wishes-gamify), 
ограниченный контекст, который добавляет возможности геймификации в «Последние пожелания».
Наконец, если вы обнаружите какую-либо проблему или исправление, или у вас возникнет предложение или комментарий 
во время чтения этой книги, вы можете создать проблему в репозитории [«DDD в проблемах книги PHP»](https://github.com/dddshelf/ddd-in-php-book-issues). 
Мы исправляем их по мере поступления. 
Если вам интересно, мы также призываем вас посмотреть эти проекты и оставить отзыв.

