# General
## О себе
## Experience
### In General
#### Проекты
##### Стек
- React + TypeScript + NestJS
- Java + Spring
- PostgreSQL, ClickHouse, SQL Server
- Graddle, Jenkins, GitLab CI, Docker, Kubernetes
#### Команды
* Первый проект: в университете в 2017 г. — веб-браузер. 5x Dev
* Внутренние системы: 3x FullStack Dev + 2x Manual QA + BA + DevOps + Support (Run Team) — в стриме из 4х команд
* Продуктовые:
	* ЮМани:
		* 3 веб команды: Frontend + Backend + QA + SA
		* 1 mobile команда: iOS + Android + QA + SA
	* ВК: 3 кросс-функциональные команды: Backend Dev + Backend QA + Web Dev + Web QA + Android Dev + Android QA + iOS Dev + iOS QA + SA + Designer
#### В какие вопросы подключался
##### Помогал другим
##### Выполнял сам
##### Делегировал другим и контролировал
| Категория вопросов                                                                      | Кому делегировал                                |
| --------------------------------------------------------------------------------------- | ----------------------------------------------- |
| Продуктовые: продуктовая стратегия, исследование рынка, влияние на продуктовые метрики, | Продакт и руководитель продуктового направления |
| Проверка работы процесса AS IS                                                          | Тестировщик                                     |
| Технические: развертывание на среды                                                     | Разработчик, эксплуатация                       |
| Отслеживание логов ошибок после развертывания                                           | Разработчик, тестировщик                        |
#### С какими стейкхолдерами работал
- Продакты и рук-ли продуктовых направлений
- Смежники: юристы, фин.проджект, СБ, саппорт, сопровождение клиентов, маркетинг
- Колл-центр: сопровождение клиентов (аккаунты), саппорт, сейлзы
- C-level: CPO, CTO, CMO, CEO, вице-президент
### Structured Narrative via SDLC
[ЮМани.HowTo.ProjectLifeCycle](https://wiki.yooteam.ru/display/PMO/HowTo.ProjectLifeCycle?preview=/135004011/372383727/Copy%20of%20PMO%20(1).jpg)
#### In General
##### 1. Идея
| Активность                                                                                                                                                                                                                                                                                                                        | С кем                                                                                            | Инпуты                                                                                                                                               | Инструменты и техники                                                          | Аутпуты                                                                                                                                                  |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| *Помощь в проверке гипотез и проведении исследований:<br>- Какие провести A/B-тесты<br>- Какие сделать Fake Door<br>- Как собрать обратную связь от пользователей: через группу сопровождения, через форму обратной связи, через UX-исследователей и тд<br>- Общение с представителями бизнеса по поводу текущих болей в системе* | Продакты и рук-ли направлений                                                                    | - Продуктовые метрики в Power BI и Superset<br>- Технические метрики в Grafana: объем данных, кол-во запросов, кол-во ошибок<br>- Обращения клиентов | - Коммуникации: 1-1, брейнштормы, воркшопы, интервью, опросы<br>- Запросы в БД | Карточка проекта (своего рода "свидетельство о рождении" проекта): контекст, решаемая проблема, стейкхолдеры, ограничения, ссылки на имеющиеся артефакты |
| *Валидация идеи со смежниками*                                                                                                                                                                                                                                                                                                    | Юристы, фин.проджект (продуктовые бухгалтеры), СБ/ИБ, саппорт, сопровождение клиентов, маркетинг | Текстовое описание идеи на понятном смежникам языке                                                                                                  | Коммуникации: почта/чаты, встречи                                              | Неформальные одобрения с возможными замечаниями                                                                                                          |
| *Оценивание проекта*                                                                                                                                                                                                                                                                                                              | Продакт, проджект, лиды                                                                          | Текстовое описание идеи                                                                                                                              | Коммуникации: встречи                                                          | -  Написание техрешения — в неделях<br>- Реализация — в неделях/месяцах/кварталах. Далее команда оценит более низкоуровнево в Story Points               |
##### 2. **Анализ и планирование**
| Активность                                    | С кем                                 | Инпуты                                                                                                                                                                                                             | Инструменты и техники                                                                                                    | Аутпуты                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| --------------------------------------------- | ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| *Ревью макетов*                               | Продакт, дизайнер                     | Драфты макетов                                                                                                                                                                                                     | Груминг макетов                                                                                                          | Набор пользовательских возможностей                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| *Документирование верхнеуровневых требований* | Продакт, дизайнер                     | - Идея<br>- Макеты                                                                                                                                                                                                 | - Фасилитация встреч<br>- Use Case, User Story, JTBD<br>- AsciiDoc, PlantUML<br>                                         | - Описание бизнес-процесса в свободной форме ("документ описывает процесс регистрации и авторизации пользователя в личном кабинете")<br>- Функциональные требования ("система должна", "пользователь должен иметь возможность")<br>- Пользовательские сценарии ("пользователь нажимает, система делает")                                                                                                                                                                                                                                                                                                                 |
| *Написание техрешения*                        |                                       | - Макеты<br>- Описание AS IS процессов: BPMN, Sequence, State/FSM, API-спеки компонентов в Swagger, логи в Kibana и Zipkin<br>- Продуктовые требования, идея<br>- Описание AS IS архитектуры в нотации C4<br>- Код | - AsciiDoc, PlantUML<br>- Sequence, State Machine<br>- Swagger, Postman, Kibana, Zipkin<br>- IDE: VS Code, IntelliJ IDEA | - Рекомендуемые контракты взаимодействия компонентов<br>- Sequence-диаграммы взаимодействия компонентов: синхронное, асинхронное (event-driven через брокеры, коллбэки, поллинги), обработка ошибок, модель данных (ERD)<br>- Текстовое описание взаимодействия компонентов, выбранные архитектурные паттерны<br>- BPMN и текстовое описание бизнес-процессов: взаимодействие пользователей и систем в рамках бизнес-процесса<br>- Нефункциональные требования: безопасность (протоколы, шифрование), обоснование выбранной СУБД (например, колоночная для дата-аналитики), перформанс, расширяемость и версионирование. |
| *Ревью техрешения*                            | Команда разработки, доменные эксперты | Драфт техрешения                                                                                                                                                                                                   | [[Peer Review]] в репозитории документации в Bitbucket                                                                   | Апрув от команды и доменных экспертов                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| *Согласование техрешения*                     | Архитекторы, CTO, смежники            | Согласованное командой техрешение                                                                                                                                                                                  | [[Peer Review]] в репозитории документации в Bitbucket                                                                   | Финальный апрув техрешения                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| *Постановка DoD проекта*                      | Продакт, проджект, рук-во             | Техрешение                                                                                                                                                                                                         | Документирование в проектной документации в Confluence                                                                   | DoD проекта:  нужно ли выкатить на бой или достаточно на тесте тк зависим от другой команды, какие фичи обязательно и какие можно урезать                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| *Создание плана проекта*                      | Продакт, проджект, лид                | - Техрешение<br>- DoD проекта<br>- [[Velocity]] report                                                                                                                                                             | - Рассчет капасити<br>- [[Gantt Chart]]                                                                                  | Активности, майлстоуны, риски и зависимости                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| *Декомпозиция на задачи разработчиков*        | Проджект, команда                     | Техрешение, макеты                                                                                                                                                                                                 | - Фасилитация встреч по декомпозиции<br>- Jira: эпики, таски, баги                                                       | Задачи в джире с оценкой в Story Points и проставленными зависимостями                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| *Синхронизация с планами других команд*       | Проджекты других команд               | План проекта: скоуп, активности, майлстоуны, риски и зависимости                                                                                                                                                   | Фасилитация встреч                                                                                                       | - Корректировка плана проекта<br>- Зафиксированные договоренности с командами                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
##### 3. **Реализация**
| Активность                                                                | С кем                      | Инпуты                                                                                                      | Инструменты и техники                                                                 | Аутпуты                                                                                             |
| ------------------------------------------------------------------------- | -------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| *Синки по проекту*                                                        | Команда                    | - Непонятности в формулировках<br>- Блокеры при реализации<br>- Непредвиденные зависимости от других команд | - Фасилитация встреч<br>- Отслеживание логов<br>- Изучение документации других систем | - Договоренности о способах решения проблем<br>- Решение проблем                                    |
| *Эксплуатационные вопросы: сетевые доступы, среды, новые компоненты и БД* | Команда, сисадмины         | - Необходимые доступы между компонентами и брокерами<br>- Схема БД                                          | Фасилитация встреч                                                                    | Согласованные с сисадминами планы подготовки инфраструктуры                                         |
| *Промежуточные демо инкрементов*                                          | Команда, продакт, проджект | Инкременты на тестовой среде                                                                                | Фасилитация встреч                                                                    | - Список критичных доработок и список пожеланий в бэклог<br>- Список изменений макетов и техрешения |
| *Решение технических и продуктовых вопросов*                              | Команда, продакт, проджект | - Макеты<br>- Техрешение<br>- План проекта                                                                  | - Фасилитация встреч<br>- Отслеживание логов<br>- Изучение документации других систем | Корректировки плана проекта: скоуп, [[Gantt Chart]]                                                 |
| *Приемка*                                                                 | Продакт, стейкхолдеры      | Инкремент на тестовой среде (или под флагом на проде)                                                       | Фасилитация встреч                                                                    | - Решение go/no-go<br>- Список критичных доработок и список пожеланий в бэклог                      |
##### 4. **Запуск и сопровождение**
| Активность                                                                                                    | С кем                                                   | Инпуты                                                                                     | Инструменты и техники                 | Аутпуты                                                            |
| ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------- | ------------------------------------------------------------------ |
| *Проведение финального демо*                                                                                  | Команда, продакт, проджект                              | Инкремент                                                                                  | Фасилитация встреч                    | Список пожеланий на дальнейшие доработки                           |
| *Уведомление об успешном запуске*                                                                             | Проджект                                                | - Развернутый на прод инкремент<br>- Ссылки на документы и пользовательские инструкции     | Email                                 | Рассылка                                                           |
| *Фикс багов, заведение техдолга*                                                                              | Команда, проджект, продакт                              | Список дефектов и пожеланий                                                                | Jira                                  | - Фикс багов<br>- Тикеты джира в техдолг                           |
| *Актуализация документации*                                                                                   | Команда                                                 | - Изначальное техрешение<br>- Реализованный код в мастере<br>- Заметки о принятых решениях | Репозиторий документации в Bitbucket  | Техрешение смержено в master-ветку документации продукта           |
| *Обсуждение проекта с командой на ближайшем [[Retrospective]]*                                                | Команда, проджект, продакт                              | - Action items с прошлого ретро                                                            | - [[Retrospective]]<br>- Доска в Miro | - Action items для выполнения<br>- Список принципов для следования |
| *Общение с группой мониторинга при возникновении инцидентов. Ответы на вопросы группы сопровождения клиентов* | - Группа мониторинга<br>- Группа сопровождения клиентов | - Инциденты<br>- Обращения пользователей                                                   |                                       | Корректировки в документах                                         |
#### На примере реального проекта
Проект: Идентификация пользователя с руководителем организации через Сбер ID

СБ

Менеджер подключения

# Версионирование API для мобилок

# Фасилитация встреч
## Подготовка
## Проведение
## Резюмирование

# Архитектурные паттерны
![[Pasted image 20240514212455.png|500]]
1. The [**circuit breaker**](https://www.redhat.com/architect/circuit-breaker-architecture-pattern) pattern minimizes the effects of a hazard by rerouting traffic to another service. While it helps make systems more fault tolerant to prevent accidents, it also requires sophisticated testing and using an infrastructure-management technology like service mesh.
2. The [**client-server**](https://www.redhat.com/architect/5-essential-patterns-software-architecture#client-server) pattern is a peer-to-peer architecture that is comprised of a _client_, which requests a service, and a _server_, which provides the the service. Examples include banking, file sharing, email, and the World Wide Web. One advantage of this pattern is that data and network peripherals are centrally managed, however, the server is expensive.
3. The [**command query responsibility segregation**](https://www.redhat.com/architect/pros-and-cons-cqrs) (CQRS) pattern handles the situation where database queries happen more often than the data changes. It separates read and write activities to provide greater stability, scalability, and performance, but it requires more database technologies and therefore may increase costs.
4. The [**controller-responder**](https://www.redhat.com/architect/5-essential-patterns-software-architecture#controller-responder) pattern divides the architecture into two components: The controller handles the data and distributes workloads, and the responder replicates data from the controller and generates results. One advantage is that you can read data from the responder without affecting the data in the controller, but if the controller fails, you may lose data and need to restart the application.
5. The [**event sourcing**](https://www.redhat.com/architect/pros-and-cons-event-sourcing-architecture-pattern) pattern is good for applications that use real-time data. It sends a continuous stream of messages to a database, web server, log, or another target. It's very flexible but demands a highly efficient and reliable network infrastructure to minimize latency.
6. The [**layered**](https://www.redhat.com/architect/5-essential-patterns-software-architecture#layered) pattern is good for e-commerce, desktop, and other applications that include groups of subtasks that execute in a specific order. The layered pattern makes it easy to write applications quickly, but a disadvantage is that it can be hard to split up the layers later.
7. The [**microservices**](https://www.redhat.com/architect/5-essential-patterns-software-architecture#microservices) pattern combines design patterns to create multiple services that work interdependently to create a larger application. Because each application is small, it's easier to update them when needed, but the complexity means you need greater architectural expertise to make everything work correctly.
8. The [**model-view-controller**](https://www.redhat.com/architect/5-essential-patterns-software-architecture#MVC) (MVC) pattern divides an application into three components. The _model_ contains the application's data and main functionality; the _view_ displays data and interacts with the user; and the _controller_ handles user input and acts as the mediator between the model and the view. This pattern enables the application to generate various views, but its layers of abstraction increase complexity.
9. The [**pub-sub**](https://www.redhat.com/architect/pub-sub-pros-and-cons) pattern sends (_publishes_) relevant messages to places that have _subscribed_ to a topic. It's easy to configure but more challenging to test because interactions between the publisher and the subscriber are asynchoronous.
10. The [**saga**](https://www.redhat.com/architect/pros-and-cons-saga-architecture-pattern) pattern is used for transactions with multiple steps, such as travel reservation services. A "saga" includes the various steps that must happen for the transaction to complete. This pattern enables transactions (ideally with five or fewer steps) to happen in loosely coupled, message-driven environments, but it requires a lot of programming and can be complex to manage.
11. The [**sharding**](https://www.redhat.com/architect/pros-and-cons-sharding) pattern segments data in a database to speed commands or queries. It ensures storage is consumed equally across instances but demands a skilled and experienced database administrator to manage sharding effectively.
12. The [**static content hosting**](https://www.redhat.com/architect/pros-and-cons-static-content-hosting-architecture-pattern) pattern is used to optimize webpage loading time. It stores static content (information that doesn't change often, like an author's bio or an MP3 file) separately from dynamic content (like stock prices). It's very efficient for delivering content and media that doesn't change often, but downsides include data consistency and higher storage costs.
13. The [**strangler**](https://www.redhat.com/architect/pros-and-cons-strangler-architecture-pattern) pattern is used when you're making incremental changes to a system. It places the old system behind an intermediary to support incremental transformation, which reduces risk compared to making larger changes. However, you need to pay close attention to routing and network management and make sure you have a rollback plan in place in case things go wrong.
14. The [**throttling**](https://www.redhat.com/architect/pros-and-cons-throttling) (or rate-limiting) pattern controls how fast data flows into a target. It's often used to prevent failure during a distributed denial of service attack or to manage cloud infrastructure costs. To use this pattern successfully, you need good redundancy mechanisms in place, and it's often used alongside the circuit breaker pattern to maintain service performance.