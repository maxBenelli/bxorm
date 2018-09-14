# Bitrix CLI

Командный интерфейс реализован на основе библиотеки `symfony/console`. Перед началом использования убедитесь, что [установили зависимости через composer](/R&D/50_bitrix_dev/06_composer/composer.md).

Исполняемый файл находится в папке bitrix:

	$ cd bitrix
	$ php bitrix.php

Для удобства вы можете создать символическую ссылку без постфикса php:

	$ chmod +x bitrix.php
	$ ln -s bitrix.php bitrix
	$ ./bitrix

Список доступных команд "из коробки":
- [orm:annotate](/R&D/50_bitrix_dev/10_orm/90_annotate.md)

Добавление своих команд планируется реализовать в ближайшее время.