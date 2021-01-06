<h2>Modelo conceitual</h2>

![alt text](https://raw.githubusercontent.com/devsuperior/sds2/master/assets/modelo-conceitual.png)

<h2>Padrão camadas adotado</h2>

![alt text](https://raw.githubusercontent.com/devsuperior/sds2/master/assets/camadas.png)

<h2>Checklist</h2>

- Setup inicial do projeto
  - Dependências
  - Arquivos .properties
  - Configuração de segurança
  
- Modelo de domínio
  - Entidades e relacionamentos
  - Mapeamento objeto-relacional
  - Seed
  
- Criar endpoints
  - [GET] /products
  - [GET] /orders
  - [POST] /orders
  - [PUT] /orders/{id}/delivered
  
- Validar perfil dev
  - Base de dados Postgres local
  - Testar todos endpoints
  
- Preparar projeto para implantação
  - Arquivo system.properties
  - Profile prod -> commit
  
- Implantar projeto no Heroku
  - Criar app e provisionar Postgres
  - Criar base de dados remota
  - Executar comandos no Heroku CLI
  
heroku login\
heroku git:remote -a <nome-do-app>\
git remote -v\
git subtree push --prefix backend heroku main
