# atc.epinetov.com-data
This data is used by atc.epinetov.com.

Меняя информацию здесь, будет изменена информация, используемая на сайте для отображения справочных материалов/генерации тестов.

Структура:
```
├───aircraft
│   └───<название_ВС>
│       └─── info.json - информация о ВС. Используется в списке ВС
├───cache
│   └───data.json - кэш всей информации. Используется при поиске
├───docs - список всей документации по ОВД
│   └───<название_документа>
│       ├───full.md - актуальный полный текст документа
│       ├───summary.md - краткое содержание документа
│       └───full-old-<id>.md - устаревший текст документа
├───posts - публикуемые элементы на странице "Полезное"
│   └───<post_id>
│       └───post.md - содержание поста
├───tests - информация, на основе которой генерируются тесты
│   └───aircraft.json - тестирование ЛТХ
│   └───trd.json - тестирование ТРД
├───aip.json - список имеющихся АИП для отображения на соответствующей странице
├───cities.json - список городов, на его основе генерируется тест с городами
├───trd.json - список всех секторов для генерации ТРД на странице с актуальной ТРД
```
