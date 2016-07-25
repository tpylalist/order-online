# Заказы онлайн
Заказы онлайн - это веб-приложение на базе фреймворка [Metadata.js](http://www.oknosoft.ru/metadata/) для интеграции с типовыми 1С

### Назначение и возможности
- Создание и редактирование документов _Заказ покупателя_ для типовых конфигураций 1С
- Заказы формируются с тем же набором и типами полей, что и в стандартной 1С (реплицируются справочники _Контрагенты, Партнеры, Договоры, Организации, Номенклатура, Характеристики, Серии, Склады_ и т.д. - все ссылочные типы, задействованные в подсистеме управления продажами)
- Фоновый двусторонний обмен изменений объектов с ИБ 1С
- Гибкая настройка видимости и доступности объектов и реквизитов для групп пользователей
- Формирование печатных форм счетов и заказов
- Формирование отчетов об оплате и отгрузке по заказам
- Поддержка автономной работы при отсутствии доступа в Интернет и прозрачного обмена с сервером при возобновлении соединения
- Синхронизация заказов не только базой поставщика, но так же и с учетными системами клиентов и дилеров

### Демо онлайн
Живое демо доступно по ссылке https://light.oknosoft.ru/orders/

### Использованы следующие библиотеки и инструменты:
#### Серверная часть
- [couchDB](http://couchdb.apache.org/), NoSQL база данных с поддержкой master-master репликации
- [nginx](http://nginx.org/ru/), высокопроизводительный HTTP-сервер
- [1c_enterprise](http://1c-dn.com/1c_enterprise/), ORM сервер 1С:Предприятие

#### Управление данными в памяти браузера
- [pouchDB](https://pouchdb.com/), клиентская NoSQL база данных с поддержкой автономной работы и репликации с CouchDB
- [alaSQL](https://github.com/agershun/alasql), база данных SQL для браузера и Node.js с поддержкой как традиционных реляционных таблиц, так и вложенных JSON данных (NoSQL)

#### UI библиотеки и компоненты интерфейса
- [dhtmlx](http://dhtmlx.com/), кроссбраузерная библиотека javascript для построения современных веб и мобильных приложений
- [handsontable](https://handsontable.com/), компонент для отображения и редактирования табличных данных
- [filesaver.js](https://github.com/eligrey/FileSaver.js), HTML5 реализация метода saveAs
- [moment.js](http://momentjs.com/), библиотека форматирования интервалов и дат
- [xlsx](https://github.com/SheetJS/js-xlsx), библиотека для чтения и записи XLSX / XLSM / XLSB / XLS / ODS в браузере

#### Графика
- [fontawesome](https://fortawesome.github.io/Font-Awesome/), набор шрифторвых иконок

### Лицензия
- Для некоммерческих Open Source проектов, разрешено использование и распространение исходного кода приложения _Заказы онлайн_ и библиотеки [Metadata.js](http://www.oknosoft.ru/metadata/) на условиях [GNU Affero General Public License v.3](http://www.gnu.org/licenses/agpl.html)
- Коммерческая [лицензия на разработчика](http://www.oknosoft.ru/programmi-oknosoft/metadata.html) позволяет использовать и распространять ПО в любом количестве неконкурирующих продуктов, без ограничений на количество копий

Данная лицензия распространяется на все содержимое репозитория, но не заменеют существующие лицензии для продуктов, используемых библиотекой metadata.js

(c) 2014-2016, компания Окнософт (info@oknosoft.ru)

