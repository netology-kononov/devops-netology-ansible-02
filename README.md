# Playbook для установки Clickhouse, Vector и Lighthouse #

## Playbook использует 3 роли. ##  
Роль AlexeySetevoi/ansible-clickhouse производит установку Clickhouse версии, указанной в переменной *clickhouse_version*.  
Установка происходит на хосты из группы *clickhouse*.

Роль netology-kononov/vector-role производит установку Vector версии, указанной в переменной *vector_version*.  
Установка происходит на хосты из группы *vector*.  

Роль netology-kononov/lighthouse-role производит установку Lighthouse.  
Установка происходит на хосты из группы *lighthouse*.  

Тэг **08-ansible-03-roles** установлен на результат выполнения домашнего задания № 8.3.
