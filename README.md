<h1 align=center>Тест-план</h1>
Тестируется новый функционал “Склады”

Функционал модуля "Склады" направленн на решение задач, связанных с учетом ресурсов. В ходе проведения тестирования будет проводиться верификация и валидация функционала модуля.

**Заказчик**: [Gectaro](https://app.gectaro.com)

<h2 align=center>Описание и документация</h2>
Основные функции нового элемента “Склады” в соответствии с технической документацией.

Основные требования:

- **Операции со складами в настройках**
- **Операции со складами внутри компании**
- **Операции со снабжением, касающиеся модуля склады, внутри компании**
- **Операции с финансами, касающиеся модуля склады, внутри компании**
- **Операции со складами внутри проекта**
- **Операции со снабжением, касающиеся модуля склады, внутри проекта**
- **Операции с финансами, касающиеся модуля склады, внутри проекта**

Спецификация по новому функционалу: [Figma](https://www.figma.com/file/CvTyKfuFa4iQSAUDVSG2nrrl/GECTARO?type=design&node-id=3568-0&mode=design&t=4A0WnAfcFBbL5BBe-0) , [YouTube](https://www.youtube.com/watch?v=JLTvHkVneCk)

Документация API : [API notion](https://skyengpublic.notion.site/API-edd2d237611546a2adb36aeb1f0f3c5c) , [swagger](https://swagger.gectaro.com/)

Будут проведены следующие виды тестирования:

**По уровню тестирования:** *Все тестирование будет проводиться на уровне приемочного тестирования в рамках альфа тестирования*

**Квадранты тестирования:** Q2 (бизнес, поддержка команды), Q3 (ориентирован на бизнес, критика продукта),

**по типам**: *функциональное* , *нефункциональное(UI, UX)*

**по исполнению кода:** *Статическое , динамическое*

**по формализации**: *сценарное*, *исследовательское*

**по видам входных данных**: *позитивное*, *негативное*

Будут применены следующие **техники тест дизайна**: *Черный ящик (класс эквивалентности*, *граничные значения, состояния переходов), основанные на опыте (Error guessing, исследовательское тестирование)*

<h2 align=center>Декомпозиция</h2>

[Таблица функционала "Склад"](https://docs.google.com/spreadsheets/d/14m8-W6WLzByRsctZwB7GucoyQi9vtmUucv__IS7RWv4/edit?usp=sharing)

<h2 align=center>Cроки тестирования</h2>

Тестировщик: **Ланцов Денис**

Start: 22:10:2023 ---> Deadline: 07.11.2023

<h2 align=center>Окружение и инструменты тестирования</h2>

**ОС**: Windows 11

**Browser**: Yandex browser Версия 23.9.2.888 (64-bit)

**ПО для тестирования API:** Postman v10.19.6

**Багтрекинговая система:** [Jira](https://lantsovotus.atlassian.net/jira/software/c/projects/GEC/issues/GEC-2)

**Тест кейсы:** [Qase](https://app.qase.io/project/GECTARO)

<h2 align=center>Артефакты тестирования</h2>

**Тест кейсы:**  [Qase](https://app.qase.io/public/report/9360aa25f47cd370be355a06df81322cc0a3d262/86825cb6264727fbde62aa0c49684ec25f1db461)

**Баг репорты:** [Jira](https://lantsovotus.atlassian.net/jira/software/c/projects/GEC/issues) [CSV](https://drive.google.com/file/d/1UU07_6hBVygf3hpYXJO77iDzRgiCzlnV/view?usp=sharing)

**Postman collection:** [Postman](https://github.com/Denubik/Testplan/blob/main/Создание%20операций%20Gectaro.json) [чек-лист проверок](https://docs.google.com/document/d/1T5aXRsKzLI1LQ9jXbn2IRltQ2ZebRQn8p1QeVpeFmFI/edit?usp=sharing)

<h2 align=center>Выводы</h2>

В ходе тестирования было заведено 29 багов. Из них 5 с высоким приоритетом, 2 со средним и 22 с низким. В следствии чего можно сделать вывод, что функционал "склады" **не готов** к релизу. Выявленные дефекты в новом функционале необходимо устранить. 

<h2 align=center>Рекомендации</h2>

Проекту необходимо начать вести документацию с требованиями к модулям, т.к. при новых итерациях продукта будет все тяжелее и тяжелее проводить регрессию, из-за отсутсвия прослеживаемости покрытия.
