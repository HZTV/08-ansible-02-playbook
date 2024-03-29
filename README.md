# 08-ansible-02-playbook
## Предисловие!


### Задание 1.
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
## Terraform
```
В main.tf написан шаблон, по которому создается и заполнятеся файл prod.yml.
В var.tf - все переменные для terrafom кода.
В instance.tf - создаются ВМ методом for_each
```

### Задание 5
![Скриншот 29-03-2024 105952](https://github.com/HZTV/08-ansible-02-playbook/assets/149588305/26549304-c638-407b-b78b-f24a006c0857)

### Задание 6
![Скриншот 29-03-2024 110112](https://github.com/HZTV/08-ansible-02-playbook/assets/149588305/2506a234-046e-4801-946a-ce3d19736978)

### Задание 7
![Скриншот 29-03-2024 110307](https://github.com/HZTV/08-ansible-02-playbook/assets/149588305/4f0f2500-ef6f-41c3-af61-157a6658bb66)
