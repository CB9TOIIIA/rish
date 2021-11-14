# RISH

SSH Web-server control panel

SSH панель конфигурации и установки web сервера 

Официальный сайт RISH https://rish.su

Протестировано на AlmaLinux (CentOS 8) и Rocky Linux

* http/2
* gzip and brotli компрессия
* mpm event для apache
* MariaDB 10.6
* Система не устанавливает никаких дополнительных сервисов и не расходует попусту ресурсов сервера
* Все актуальные версии PHP начиная с 7.2 (список держится в актуальном состоянии)
* Есть возможность установки Joomla

Команда установки

    curl get.rish.su | sh

Возможно, что в минимальной установке CentOS будет отсутствовать команда curl и ее понадобится установить отдельно:

    yum install curl

