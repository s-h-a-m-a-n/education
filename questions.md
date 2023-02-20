# Схема отказоустойчивости реализованных сервисов
# Механизмы балансировки нагрузки между репликами
# Какие варианты масштабирования можно реализовать на технологиях Точки?
# Consul, DNS, кластера
# Какие требования к реализации сервиса для его масштабирования?

# Асинхронное и Синхронное взаимодействие: особенности, преимущества и недостатки
# Гарантия доставки сообщений (exactly-once, at-least-once, at-most-once)
# Обработка ошибок
# Отправка сообщений, транзакции (2PC, Best Efforts 1PC, Transactional Outbox)
# Получение сообщений (параллельная обработка, порядок сообщений, дубли)
# Паттерны интеграции
# Брокеры сообщений: особенности, внутренее устройство, выбор.

- [Приложение 12-факторов](https://12factor.net/ru/)
- [Балансировка нагрузки](https://www.haproxy.com/blog/loadbalancing-faq/)
- [Методы балансировки нагрузки при масштабировании](https://www.haproxy.com/blog/load-balancing-affinity-persistence-sticky-sessions-what-you-need-to-know/)
- [Sharding for Scale - Скалирование сервиса через шардирование](https://devops.com/sharding-scale-architecture-matters/)
- [Принципы шардирования на примере БД](https://www.digitalocean.com/community/tutorials/understanding-database-sharding)
- [Паттерны отказоустойчивости](https://www.amazon.com/Patterns-Tolerant-Software-Robert-Hanmer/dp/0470319798)
- [Доклад Горизонтальное масштабирование](https://www.youtube.com/watch?v=M20tzOy36rs)
- [Введение в балансировку систем](https://medium.com/southbridge/introduction-to-modern-network-load-balancing-and-proxying-52e8ca36adde)
- Пройти [курс](http://highload.guide/blog/what_data_we_have.html) по масштабированию и отказоустойчивости от highload
- [Discovery with Consul at scale](https://medium.com/criteo-labs/discovery-with-consul-at-scale-1d6808202d86)
- [Использование Consul для масштабирования stateful-сервисов](https://habr.com/ru/company/pixonic/blog/424777/)
- [Паттерны для отказоустойчивости (англ., пдф)](https://hillside.net/europlop/HillsideEurope/Papers/EuroPLoP2002/2002_Saridakis_ASystemOfPatternsForFaultTolerance.pdf)
- [Общие правила типов сообщений](https://confluence.bank24.int/pages/viewpage.action?pageId=34603288)
- [RabbitMQ vs Kafka](https://jack-vanlightly.com/blog/2017/12/3/rabbitmq-vs-kafka-series-introduction)
- RabbitMQ против Kafka [часть 1](https://habr.com/ru/company/itsumma/blog/416629/), [часть 2](https://habr.com/ru/company/itsumma/blog/418389/), [часть 3](https://habr.com/ru/company/itsumma/blog/437446/)
- [Enterprise Integration Patterns](https://www.enterpriseintegrationpatterns.com/)
- [Распределенные транзакции (XA) с помощью JTA в JavaSE](http://samolisov.blogspot.com/2011/02/xa-jta-javase-spring-atomikos-2.html)
- [Distributed transactions in Spring, with and without XA](https://www.infoworld.com/article/2077963/distributed-transactions-in-spring--with-and-without-xa.html)
- [Transactional Outbox](https://medium.com/@forketyfork/transactional-outbox-a-simplified-approach-8127158ffc91)
- [Designing atomicity and resiliency when publishing to the event bus](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/multi-container-microservice-net-applications/subscribe-events#designing-atomicity-and-resiliency-when-publishing-to-the-event-bus)
- [Как правильно выбирать очередь](https://docs.tochka-tech.com/learning-resources/ontico/hl-202105/hl-202105-1/)
