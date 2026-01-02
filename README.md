# results-task
### Файл №3
# Используем localhost для тестирования
```
[test_servers]
localhost ansible_connection=local

[development]
dev1.local ansible_host=127.0.0.1 ansible_connection=local
dev2.local ansible_host=127.0.0.1 ansible_connection=local
dev3.local ansible_host=127.0.0.1 ansible_connection=local
dev4.local ansible_host=127.0.0.1 ansible_connection=local
dev5.local ansible_host=127.0.0.1 ansible_connection=local

[all:children]
test_servers
development
```

### Файл №4 

