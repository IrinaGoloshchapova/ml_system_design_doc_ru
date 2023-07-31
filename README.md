# ML System Design Doc - Reliable ML
*[Шаблон документа для дизайна ML-систем](https://github.com/IrinaGoloshchapova/ml_system_design_doc_ru/blob/main/ML_System_Design_Doc_Template.md) от телеграм-канала [Reliable ML](https://t.me/reliable_ml)*   


## Что такое ML System Design Doc

ML System Design документ - это по сути сводный план по построению системы машинного обучения для решения конкретного запроса бизнеса в вашей компании. 
Его стоит применять на этапе дизайна вашей системы, чтобы в итоге ваше решение было полезным для бизнеса, а именно: могло быть внедрено, работало после внедрения и приносило реальную пользу.  

А для того, чтобы этот план было проще построить, и чтобы итоговая система, действительно, приводила к результату, мы в сообществе [Reliable ML](https://t.me/reliable_ml) разработали [шаблон такого документа](https://github.com/IrinaGoloshchapova/ml_system_design_doc_ru/blob/main/ML_System_Design_Doc_Template.md).  

![image](https://user-images.githubusercontent.com/12476970/227248587-11e2f92f-51ad-4edb-9eab-1dc4b8f8e902.png)

## Зачем нужен ML System Design Doc

Дизайн-документ, созданный на этапе проектирования системы, помогает Data Science подразделению:  

* [x] Структурировать собственные мысли: БТ, архитектура решения, результат, применение   
* [x] Задать все критические вопросы бизнесу, уточнить бизнес-требования  
* [x] Понять бизнес-процесс и нюансы применения ML-системы  
* [x] Понять, что реализация проекта возможна и какие ожидают трудности  
* [x] Синхронизировать ожидания технической и бизнес-команд  
* [x] Установить стандарты работы  

## Как составить ML System Design Doc

- Скачать [шаблон документа от Reliable ML](https://github.com/IrinaGoloshchapova/ml_system_design_doc_ru/blob/main/ML_System_Design_Doc_Template.md) и загрузить его в общее рабочее пространство вашей компании или сделать форк репозитория и работать в нем
- Прочитать краткие рекомендации по процессу заполнения документа (workflow) - [здесь](https://github.com/IrinaGoloshchapova/ml_system_design_doc_ru/blob/main/ML_System_Design_Doc_Workflow.md).  
- Посмотреть детальный доклад о том, что такое ML System Design Doc и о том, как, когда и зачем его составлять - [тут](https://www.youtube.com/watch?v=PW9TGNr1Vqk).  
- Приступить к работе!  
 
## Примеры дизайн-документов по шаблону Reliable ML

- [**FMCG компания - Прогнозирование выручки в магазинах**](https://github.com/Chuguevskij/ml_system_design_doc_Revenue_in_shops). Автор: [@Chuguevskij](https://github.com/Chuguevskij).  Бизнес цель – замена ручной работы прогнозами модели, которые будут использоваться для: составления плана продаж в магазинах на следующие 6 месяцев и сегментации магазинов на основе продаж для применения определенной стратегии взаимодействия.  
- [**Девелопер коммерческой недвижимости - Рекомендательная система для сделок по аренде недвижимости**](https://github.com/nikita4099/otelit/blob/main/README.md). Автор: [@nikita4099](https://github.com/nikita4099). Бизнес-цель – с помощью увеличения релевантности предложения компании для клиента повысить среднюю конверсию из лида в успешную сделку для арендаторов.
- [**Лента - Сервис кластеризации магазинов**](https://github.com/leafea94/ml_system_design_doc_clustering). Автор: [@leafea94](https://github.com/leafea94). Бизнес-цель -  помочь бизнесу в быстром принятии решений с помощью инструмента для автоматической группировки магазинов по базовым метрикам, важным для ритейла. Один из типовых возможных сценариев использования инструмента - адаптация CVP (Customer Value Proposition) с учетом кластеров. [Доклад автора дизайн документа](https://www.youtube.com/watch?v=pdnisiS-csk) с детальным рассказом об опыте его составления.  

## Как обратиться в Reliable ML за поддержкой

- Команда [Reliable ML](https://t.me/reliable_ml) готова помочь вам с работой над составлением дизайн-документа - включая ревью самой системы.  
- В приоритете проекты, которые готовы выложить финальный документ в открытый доступ (без NDA части) - как в разделе выше.  
- Пишите [@irina_goloshchapova](https://t.me/irina_goloshchapova) и [@promsoft](https://t.me/promsoft)  
  
## Материалы для дополнительного погружения в тему  
- [Шаблон ML System Design Doc [EN] от AWS](https://github.com/eugeneyan/ml-design-docs) и [статья](https://eugeneyan.com/writing/ml-design-docs/) с объяснением каждого раздела  
- [Верхнеуровневый шаблон ML System Design Doc от Google](https://towardsdatascience.com/the-undeniable-importance-of-design-docs-to-data-scientists-421132561f3c) и [описание общих принципов его заполнения](https://towardsdatascience.com/understanding-design-docs-principles-for-achieving-data-scientists-53e6d5ad6f7e).
- [ML Design Template](https://www.mle-interviews.com/ml-design-template) от ML Engineering Interviews  
- Статья [Design Documents for ML Models](https://medium.com/people-ai-engineering/design-documents-for-ml-models-bbcd30402ff7) на Medium. Верхнеуровневые рекомендации по содержанию дизайн-документа и объяснение, зачем он вообще нужен  
- [Краткий Canvas для ML-проекта от Made with ML](https://madewithml.com/courses/mlops/design/#timeline). Подходит для верхнеуровневого описания идеи, чтобы понять, имеет ли смысл идти дальше.  
