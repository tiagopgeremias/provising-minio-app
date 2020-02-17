## Executando o playbook de provisionamento de Ambiente.
```ansible-playbook -i inventory/hosts -k start-provision.yml```



ansible-playbook -k -K -i inventory/hosts start-provision.yml --extra-vars "minio_access=ubuntuteste" --extra-vars "minio_secret=ubuntuteste"