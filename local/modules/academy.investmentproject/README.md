### Создание ORM аннотаций
- Установить `composer`, инструкция: https://getcomposer.org/download/;
- Выполнить `COMPOSER=composer-bx.json composer install`, находясь в директории `<docroot>/bitrix/`;
- Дать право выполнения файлу `<docroot>/bitrix/bitrix.php`: `chmod +x bitrix.php`;
- Выполнить `./bitrix.php orm:annotate -m <module.name> <moduleRoot>/meta/orm.php`;