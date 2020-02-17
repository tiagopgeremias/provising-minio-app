## Executando o playbook de provisionamento de Ambiente.
```ansible-playbook -k -i inventory/hosts start-provision.yml --extra-vars "minio_access=ubuntuteste" --extra-vars "minio_secret=ubuntuteste"```



