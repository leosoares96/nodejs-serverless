"# nodejs-serverless"

### Comando para criação do projeto com template nodejs

serverless create --template aws-nodejs --path nodejs-serverless

### Configuração da chave de acesso da AWS obtida em IAM

serverless config credentials --provider aws --key=xxx --secret xxx

### Realizar deploy do script no Lambda e no S3

serverless deploy -v

### executar a função

serverless invoke -f hello -l

### deleta tudo que esta relacionado a essa função

serverless remove
