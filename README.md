**Название:** Генератор ключей продукта

**Описание:** Плагин для Xenforo Resource Manager, который добавляет возможность генерировать уникальные ключи продукта для ресурсов, размещенных в Xenforo Resource Manager. 

**Функции:**

* Генерация уникальных ключей продукта для ресурсов.
* Просмотр ключа продукта в отдельной вкладке ресурса.
* Настройка формата ключа продукта.
* Настройка префикса и суффикса ключей продукта.

**Планы на будущее:**

* Добавление API для проверки валидности ключей.
* Возможность настройки длины ключа.
* Возможность включения/отключения генерации ключей для конкретных типов ресурсов.
* Возможность экспорта ключей в формате CSV.

### Структура папок:

```
├── src
│   ├── XF
│   │   └── MGDesigma
│   │       └── ProductKeyGenerator
│   │           ├── Listener
│   │           │   └── ProductKeyGeneratorListener.php
│   │           ├── Controller
│   │           │   └── ProductKeyGeneratorController.php
│   │           ├── Public
│   │           │   └── Controller
│   │           │       └── ProductKeyGeneratorPublicController.php
│   │           ├── Model
│   │           │   └── ProductKeyGeneratorModel.php
│   │           ├── Setup
│   │           │   └── ProductKeyGeneratorSetup.php
│   │           └── Helper
│   │               └── ProductKeyGeneratorHelper.php
│   ├── addon.json
│   ├── templates
│   │   ├── public
│   │   │   └── product_key_generator.less
│   │   ├── admin
│   │   │   └── product_key_generator_options.less
│   │   └── admin
│   │       └── product_key_generator_options.js
│   ├── Resources
│   │   └── public
│   │       └── js
│   │           └── product_key_generator.js
│   ├── uninstall.php
│   └── install.php
```


**Автор:** MGDesigma

**Лицензия:** GPL-3.0
