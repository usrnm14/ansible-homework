# ansible-homework
Плейбук написан без использования готовых ролей

Окружение в котором происходила отладка:
- 3 виртуалки на CentOS 8.3.2011
- общая учетка root с общим паролем для всех хостов

Запуск плейбука:
```
ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook --ask-pass site.yml -i inventory/hosts
```
