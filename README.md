# 08-ansible-02-playbook
## Предисловие!

Файл prod.yml генерируется после выполнения кода terraform и имеет общий вид:
```
clickhouse:
  hosts:
    clickhouse-01: 
      ansible_host: 84.201.133.75
      ansible_user: ubuntu
  
vector:
  hosts:
    vector-01: 
      ansible_host: 158.160.40.12
      ansible_user: ubuntu
```
