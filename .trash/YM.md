---

kanban-plugin: board

---

## To be Processed



## To Do

- [ ] #agile-qr Убрать lifecycleId из ручек


## Waiting to Hear Back from

- [ ] #offer-sign Ваня Скоков скажет какой план на аналитику проекта. См. тред на почте
- [ ] stage-1 #access-code
- [ ] #enter-data-on-client  Подготовиться к logic review
- [ ] #enter-data-on-client stage-1


## Done

**Complete**
- [x] #agile-qr Убрать про гет-параметр редиректа на страницу создания счета
- [x] Заполнить опрос на продактов б2б
- [x] #agile-qr  Дима попов ответит ок ли в записи invoice_payment сохранять id гибкого QR если счет на момент оплаты был привязан к гибкому QR
- [x] #agile-qr 
	Витя ответит Косте 2 https://bitbucket.yooteam.ru/projects/PRODUCT-SPECS/repos/yookassa-dashboard/pull-requests/162/overview?commentId=1068556
- [x] #agile-qr Витя ответит Косте 1 https://bitbucket.yooteam.ru/projects/PRODUCT-SPECS/repos/yookassa-dashboard/pull-requests/162/overview?commentId=1068549
- [x] Отписаться дейли
- [x] #agile-qr stage-2
- [x] #agile-qr Ограничить привязку гибкого куара только к тип=ссылка+qr. Уточнить в чате у Вити
- [x] #agile-qr В сценарии отображения гибкого куара возвращать инфу о привязанном счете отдельным вызовом /getInvoiceDetails вместе с признаками доступности привязки-отвязки
- [x] Поправить верстку: **dashboard** сравнивает полученный `invoiceId` с тем, который сейчас привязан к гибкому QR:
	
	|   |   |
	|---|---|
	||Необходимо на случай изменений в БД в то время пока пользователь висел в интерфейсе. …​.. Если НЕ совпадает, то возвращает ошибку|
- [x] #agile-qr Добавить поле Status в ответы ручек на будущее когда будет много-куарность
- [x] #agile-qr  На карточку деталей счета добавить действие отвязки. Добавить в ответ ручки /getInvoiceDetails
- [x] #agile-qr Добавить поле Status на сущности гибкого QR на будущее когда будет много-куарность
- [x] #agile-qr  На карточку привязанного счета добавить действие отвязки. Добавить в ответ ручки /agile-qr/get
- [x] #enter-data-on-client Договориться с Катей о плане на ревью
- [x] #enter-data-on-client Актуализировать и поправить ТР
- [x] #offer-sign Спросить у Вани Скокова когда аналитик ДВС приступит к работе
- [x] Удалить ВБшный профиль OpenVPN с ноута юмани
- [x] Убрать мерж-конфликт #access-code
- [x] #agile-qr Витя и/или Юля ответят должна ли быть возможность просматривать детали счета в шторе из истории привязки счетов к гибкому куару @[[2024/07-04]]
- [x] #agile-qr Launch devsol @[[&/2024-07-04]]
- [x] stage-1 @[[2024/07-04]] #agile-qr
- [x] Гера ответит по поводу Экомбанк+CRM
- [x] #agile-qr Вернуть шаги про историю счетов кроме как отображение и возврат на фронт
- [x] Комменты Димы Х. #agile-qr
- [x] Изучить имейлы #offer-sign
- [x] Новые комменты Димы Попова #agile-qr
- [x] Ответить на комменты Димы Попова #agile-qr @[[2024/07-04]]
- [x] #agile-qr В шаги отображения истори привязок-отвязок добавить шаги про получение деталей счетов для отображения на фронте. Также добавить что фронт должен отобразить
- [x] Решить вопрос с CRM по поводу получения платежей из ЧИ
- [x] BI ответят по поводу аналитики счетов в МИ #analytics @[[2024/07-03]]
- [x] Комменты Кеши #access-code @[[2024/07-01]]
- [x] BI ответят по поводу getPaymentToAccount. Ответить Вите нужны ли доработки в БиАй или ДВС, или только в ЛК #analytics @[[2024/07-02]]
- [x] #femida Обсудить стейджи и ФСМ-процессы с командой. Поправить ТР: стейджи и 2vs1 ФСМ-процесс @[[2024/07-02]]
- [x] Подготовиться к LogicReview agile-qr #agile-qr  @[[2024/07-02]]
- [x] Обсудить с Ваней кто будет делать сервис счетов в апи. Я хочу взять на себя  @[[2024/07-01]] #an
- [x] Никита Иванов ответит по поводу https://nexus.yooteam.ru/repository/api-specification-release/private/checkout-info-specification/latest/checkout-info-specification.html#/Orders/post_api_orders_lk_list_for_shops #zk @[[2024/07-03]]
- [x] #femida Илья и другие бэкендеры ответят по поводу разделения объединения ФСМ-процессов	@[[2024/07-01]]




%% kanban:settings
```
{"kanban-plugin":"board","list-collapse":[false,false,false,true],"lane-width":300}
```
%%