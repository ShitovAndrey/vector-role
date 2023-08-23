Install Clickhouse & Vector Ansible-Playbook
=========
Роль позволяет выполнит установку и настройку Vector.


Role Variables
--------------

|       Параметр      | Тип    | Значение по умолчанию | Описание                                                                |
|------------------------|--------|-----------------------|-------------------------------------------------------------------------|
| vector_user            | string | vector                | Задает имя пользователя от которого будет запущен systemd unit          |
| tmp_directory_path     | string | /tmp/distrib          | Задает путь для временной директории в которую загружаются дистрибутивы |
| vector_version         | string | 0.31.0                | Позволяет задать требуемую к установки версию Vector                    |

Tags
------------

 - prod - При запуске плейбука с эти тэгом, будет выполнен таск по очистки содержимого во временной директории.

Author Information
------------------

AndreyShitov