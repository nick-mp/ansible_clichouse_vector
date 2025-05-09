# Домашнее задание к занятию 2 «Работа с Playbook»

   ![Task](https://github.com/nick-mp/ansible_clichouse_vector/blob/main/img/logo_Vector.png)

   ![Task](https://github.com/nick-mp/ansible_clichouse_vector/blob/main/img/logo_ClickHouse.png)

## Version 

clickhouse_version: "22.3.3.44"
vector_version: "0.39.0"

### Prerequisite

- **Ansible 2.9+**

### Configure

In the file `inventories/host.yml` configure the node details.

### Install


    # Deploy with ansible playbook - run the playbook as root

 
5. `ansible-lint site.yml` ошибок не нашел, результат видно в п.6
6. Попробуйте запустить playbook на этом окружении с флагом `--check`.

   ![Task](https://github.com/nick-mp/ansible_clichouse_vector/blob/main/img/5-6.png)


7. Запустите playbook на `prod.yml` окружении с флагом `--diff`. Убедитесь, что изменения на системе произведены.

   ![Task](https://github.com/nick-mp/ansible_clichouse_vector/blob/main/img/7.png)

8. Повторно запустите playbook с флагом `--diff` и убедитесь, что playbook идемпотентен.

   ![Task](https://github.com/nick-mp/ansible_clichouse_vector/blob/main/img/8.png)

9. Подготовьте README.md-файл по своему playbook. В нём должно быть описано: что делает playbook, какие у него есть параметры и теги. Пример качественной документации ansible playbook по [ссылке](https://github.com/opensearch-project/ansible-playbook). Так же приложите скриншоты выполнения заданий №5-8
10. Готовый playbook выложите в свой репозиторий, поставьте тег `08-ansible-02-playbook` на фиксирующий коммит, в ответ предоставьте ссылку на него.

---

### Как оформить решение задания

Выполненное домашнее задание пришлите в виде ссылки на .md-файл в вашем репозитории.