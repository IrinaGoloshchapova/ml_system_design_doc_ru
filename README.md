# ML System Design Doc - Reliable ML
*[Шаблон документа для дизайна ML-систем](https://github.com/IrinaGoloshchapova/ml_system_design_doc_ru/blob/main/ML_System_Design_Doc_Template.md) от телеграм-канала [Reliable ML](https://t.me/reliable_ml)*   


## Что такое ML System Design Doc

ML System Design документ - это по сути сводный план по построению системы машинного обучения для решения конкретного запроса бизнеса в вашей компании. 
Его стоит применять на этапе дизайна вашей системы, чтобы в итоге ваше решение было полезным для бизнеса, а именно: могло быть внедрено, работало после внедрения и приносило реальную пользу.  

А для того, чтобы этот план было проще построить, и чтобы итоговая система, действительно, приводила к результату, мы в сообществе [Reliable ML](https://t.me/reliable_ml) разработали [шаблон такого документа](https://github.com/IrinaGoloshchapova/ml_system_design_doc_ru/blob/main/ML_System_Design_Doc_Template.md).  

Шаблон был успешно адаптирован уже в более 10 крупных компаниях на российском рынке, а также внедрен Университетом ИТМО в программу [онлайн-магистратуры по ML-инженерии](https://ai.itmo.ru/) как ключевой инструмент планирования ML-проектов.  

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
- Если остались вопросы - заглянуть в [раздел допматериалов](https://github.com/IrinaGoloshchapova/ml_system_design_doc_ru#%D0%BC%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B-%D0%B4%D0%BB%D1%8F-%D0%B4%D0%BE%D0%BF%D0%BE%D0%BB%D0%BD%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE-%D0%BF%D0%BE%D0%B3%D1%80%D1%83%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B2-%D1%82%D0%B5%D0%BC%D1%83).
- Приступить к работе!  
 
## Примеры дизайн-документов по шаблону Reliable ML

- [**Прогнозирование выручки в магазинах - FMCG компания**](https://github.com/Chuguevskij/ml_system_design_doc_Revenue_in_shops). Автор: [Михаил Масагутов](https://github.com/Chuguevskij).  Бизнес цель – замена ручной работы прогнозами модели, которые будут использоваться для: составления плана продаж в магазинах на следующие 6 месяцев и сегментации магазинов на основе продаж для применения определенной стратегии взаимодействия. [Доклад](https://www.youtube.com/watch?v=mInWeBfhrG8) автора об опыте составления дизайн-документа.
- [**Рекомендательная система для сделок по аренде недвижимости - Девелопер коммерческой недвижимости**](https://github.com/nikita4099/otelit/blob/main/README.md). Автор: [Никита Артемьев](https://github.com/nikita4099). Бизнес-цель – с помощью увеличения релевантности предложения компании для клиента повысить среднюю конверсию из лида в успешную сделку для арендаторов.
- [**Сервис кластеризации магазинов - Лента**](https://github.com/leafea94/ml_system_design_doc_clustering). Автор: [Любава Ткаченко](https://github.com/leafea94). Бизнес-цель -  помочь бизнесу в быстром принятии решений с помощью инструмента для автоматической группировки магазинов по базовым метрикам, важным для ритейла. Один из типовых возможных сценариев использования инструмента - адаптация CVP (Customer Value Proposition) с учетом кластеров. [Доклад](https://www.youtube.com/watch?v=pdnisiS-csk) автора об опыте составления дизайн-документа.
- [**Антифрод система для проведения транзакций в банке - ML System Design Doc Challenge, Data Fest 2023**](https://github.com/dmitrii-naumenko/DDC2023/blob/main/ML%20System%20Design%20Doc.md). Авторы: [Дмитрий Науменко](https://github.com/dmitrii-naumenko), [Сергей Артюхин](https://github.com/serart), [Артем Савельев](https://github.com/w3ban), [Эдуард Поляков](https://github.com/Edipool), [Сабрина Садиех](https://github.com/SadSabrina). Бизнес-цель - увеличение эффективности банковской системы антифрода для снижения финансовых и репутационных рисков связанных с мошенническими действиями. [Выступление](https://www.youtube.com/watch?v=fX7PhT6iY8M) и [презентация](https://docs.google.com/presentation/d/18pzumNy8zM8o7m-zHOwHt3S4ec16g6Nz/edit?usp=drive_link&ouid=112881147081820621929&rtpof=true&sd=true) авторов дизайн-дока на финале контеста ML System Design Doc Challenge, проводимого [Мариной Завгородней](https://github.com/mzav) на Data Fest 2023.
- [**PostFinder - Чат-бот для поиска ответов в телеграм-каналах**](https://github.com/torchme/PostFinder/blob/main/docs/designdoc.md). Авторы: [Данил Картушов](https://github.com/torchme), [Тимбал Данил](https://github.com/Artfuuul), [Устинов Кирилл](https://github.com/umbilnm), [Соколов Федор](https://github.com/mayb333), [Дмитрий Клименченко](https://github.com/dimages). Бизнес-цель - Улучшение доступа к информации в телеграм-каналах через автоматизированный поиск ответов с помощью чат-бота.

## Как обратиться в Reliable ML за поддержкой

- Команда [Reliable ML](https://t.me/reliable_ml) готова помочь вам с работой над составлением дизайн-документа - включая ревью самой системы.  
- В приоритете проекты, которые готовы выложить финальный документ в открытый доступ (без NDA части) - как в разделе выше.  
- Пишите [@irina_goloshchapova](https://t.me/irina_goloshchapova) и [@promsoft](https://t.me/promsoft)  
  
## Материалы для дополнительного погружения в тему  

### Материалы по ML System Design от Reliable ML  

- О поиске идей для ML-проектов и о дизайн-документе простыми словами ([лекция](https://www.youtube.com/watch?v=HmdKhI2_6Os), [слайды](https://drive.google.com/drive/folders/1sfPg8M4MAjPL4xsOlcBb7t8L-FI1nrqW))
- Детально о работе с дизайн-доком ([лекция](https://www.youtube.com/watch?v=PW9TGNr1Vqk), [слайды](https://storage.yandexcloud.net/ds-ods/files/content/2023/01/05/8dc6bb3292e0/Reliable_ML%20-%20ML%20System%20Design%20Doc.pdf))
- Про интеграцию ML-моделей в бизнес-процессы ([лекция](https://www.youtube.com/watch?v=4K53wAeXPg0), [слайды](https://storage.yandexcloud.net/ds-ods/files/content/2023/01/05/b2b37c76a787/Reliable_ML_%D0%98%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D1%8F_%D0%B2_%D0%B1%D0%B8%D0%B7%D0%BD%D0%B5%D1%81_%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D1%8B.pdf))
- Курс [ML System Design 2023](https://ods.ai/tracks/ml-system-design-23) и [ML System Design 2022](https://www.youtube.com/playlist?list=PLTlO6nV_TaGDu_HYG8cm7iUFZ_4qEJAYF)
- [Критерии оценки дизайн-документов](https://github.com/IrinaGoloshchapova/ml_system_design_doc_ru/blob/main/checklist.md) от ИТМО & Reliable ML

### Международная практика по ML System Design Docs  

- [Шаблон ML System Design Doc [EN] от AWS](https://github.com/eugeneyan/ml-design-docs) и [статья](https://eugeneyan.com/writing/ml-design-docs/) с объяснением каждого раздела  
- [Верхнеуровневый шаблон ML System Design Doc от Google](https://towardsdatascience.com/the-undeniable-importance-of-design-docs-to-data-scientists-421132561f3c) и [описание общих принципов его заполнения](https://towardsdatascience.com/understanding-design-docs-principles-for-achieving-data-scientists-53e6d5ad6f7e).
- [ML Design Template](https://www.mle-interviews.com/ml-design-template) от ML Engineering Interviews  
- Статья [Design Documents for ML Models](https://medium.com/people-ai-engineering/design-documents-for-ml-models-bbcd30402ff7) на Medium. Верхнеуровневые рекомендации по содержанию дизайн-документа и объяснение, зачем он вообще нужен  
- [Краткий Canvas для ML-проекта от Made with ML](https://madewithml.com/courses/mlops/design/#timeline). Подходит для верхнеуровневого описания идеи, чтобы понять, имеет ли смысл идти дальше.  
