# Projeto classificados como utilizar

1) Abra o terminal e acesse a pasta htdocs do XAMPP
   - cd C:\xampp\htdocs

2) Clonar o repositório para a pasta htdocs
   - git clone https://github.com/carolinacabril/classificados.git

3) Abrir a pasta CLASSIFICADOS no editor de códigos de sua preferência

4) Iniciar os módulos APACHE e MYSQL do XAMPP

5) Abrir o phpmyadmin e criar um novo banco de dados com o nome db_classificados

6) Importar o arquivo banco_de_dados.sql que está na pasta CLASSIFICADOS para o banco criado

7) Acessar o arquivo config.php e verificar se a informações de banco de dados no módulo PDO estão corretas
  new PDO("mysql:dbname=nome_do_banco_de_dados;host=localhost","seu_usuario","sua_senha");

8) Abrir a url para acessar o sistema http://localhost/classificados/index.php
