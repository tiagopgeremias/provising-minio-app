## Executando o playbook de provisionamento de Ambiente.

```ansible-playbook -K -i inventory/hosts start-provision.yml --extra-vars "minio_access=USUARIO_MIN.IO" --extra-vars "minio_secret=SENHA_MIN.IO"```


- Configura o ambiente
- Baixa e inicia a aplicação do Min.io
- Atualiza o sistema
- Instala o Python 3 e pip3
- Instala o modulo pipenv
- Clona o projeto https://github.com/tiagopgeremias/minio-upload.git
- Instala dependencias do projeto
- Inicia a aplicação em Flask
- Cria um arquivo de exemplo em /tmp/
- Envia o arquivo por meio de requisição POST para aplicação Flask
