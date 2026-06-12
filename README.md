# MEPHI Session Project 2026

## Выполненные задачи

- Настроено сетевое подключение и hostname
- Проверена сетевая связность с локальной сетью и внешними ресурсами
- Установлены и настроены nginx, tcpdump и libcap-ng-utils
- Выполнена работа с RPM-пакетами
- Создана и настроена файловая система ext4 с автоматическим монтированием через `/etc/fstab`
- Настроен запуск nginx при загрузке системы
- Созданы пользователь `mephi-admin` и группа `mephi-devs`
- Настроены права доступа (DAC) и SELinux (MAC)
- Настроены capabilities для запуска tcpdump без привилегий root
- Ограничен вход пользователя root через PAM
- Развернута персонализированная web-страница и проверена её доступность по HTTP

## Содержимое репозитория

В репозитории представлены все артефакты, требуемые заданием:

- `project_history.txt`
- `network_check.txt`
- `nginx_recent_logs.txt`
- `fstab.txt`
- `selinux_status.txt`
- `file_contexts.txt`
- `tcpdump_capabilities.txt`
- `permissions.txt`
- `users_groups.txt`
- `index.html`
- `curl_output.txt`
- `mephi-nginx-screenshot.png`
- `tcpdump-*.rpm`

## Результат

Web-сервер nginx успешно публикует страницу:

Hello from Student: ДН068
