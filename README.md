M5-Grupo-back-end A ideia desse projeto é criar uma API no padrão REST com CRUD, para integrar o front end com o banco de dados, visando assim executar todas a operações necessárias.

Para executar essa API é necessário instalar os seguintes módulos e o framework Express, seguindo os comandos abaixo dentro do terminal.

npm init

npm install express

npm install sequelize sqlite3

npm install -g nodemon

npm install --save-dev nodemon

Depois executar o script createTable.js que está na pasta src/utils com o comando abaixo, para criar as tabelas no banco de dados.

node createTable.js

Para executar a API é só dar o seguinte comando abaixo no arquivo server.js que está dentro da pasta src.

node server.js
## Referência

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

