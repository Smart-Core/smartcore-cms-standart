Smart Core CMS Standart Edition
===============================
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Smart-Core/chat?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

The modern system for creating and managing web projects with open source, based on the Symfony2 Framework.

Install
-------

Step 1: Create database 

Step 2: Install new folder mysite.com

``` bash
composer create-project smart-core/cms mysite.com
```

Or to current folder

``` bash
composer create-project smart-core/cms ./
```

Login as new user into http://my-projeсt/admin/.

Пройти в раздел "Структура", по адресу `http://my-projeсt/admin/structure/` и создать главную папку.

Создать "Хранилище" для медиаколлекции, по адресу:
`http://my-projeсt/admin/config/media/storage_create/`

Для модулей, которые будут использовать медиаколлекцию, нужно создать коллекции по адресу:
`http://my-projeсt/admin/config/media/collection_create/`
