# docker-laravel
dockerfile e docker-compose para projetos Laravel. Utiliza PHP 7.4 e Mysql latest

# Instruções

* Copie os arquivos php.dockerfile e docker-compose.yml para a raíz de seu projeto
* Crie uma pasta na raiz do seu projeto chamada "volume" e dentro dela crie uma pasta chamada "mysql"
* Edite a variável DB_HOST do seu .env para "mysql"
* Rode o comando docker-compose up para iniciar o projeto
* acesse http://localhost para visualizar o projeto rodando
