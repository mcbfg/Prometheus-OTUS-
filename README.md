Развернул 2 ВМ на базе RockyLinux 9.5 (1- Prometheus Server, 2- CMS)
Установил и настроил Prometheus на этот же сервер добавил node_exporter (Все поднялось удачно)
На CMS установил NGINX, Postgresql установил и настроил node_exporter, blackbox_exporter, postgresql_exporter. Открыл порты на firewall
На сервере Prometheus добавил job'ы для сбора метрик со всех exporter'ов
