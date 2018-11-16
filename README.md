# Teste backend BW2 Digital - Star Wars API

Aplicação desenvolvida para a B2W Digital, baseada no universo de Star Wars.
Nesta aplicação foram implementadas as seguintes fucionalidades: adicionar planetas, listar planetas, buscar por nome e Id, remover planeta.
Foi feito totalmente em Node.

# TECNOLOGIAS UTILIZADAS

- Node.js 10.13.0

- Postman v6.5.2

- MongoDB 4.0.4

# DEPENDÊNCIAS

- Express 4.16.4

- Mongoose 5.3.12

- Body-Parser 1.18.3

- Nodemon (não é pré-requisito)


# GUIA 

1. É necessário clonar o repositório com o comando git clone https://github.com/brunoalvaress/b2wdigital-testebackend-bruno.git
2. Entrar no diretório do clone com cd b2wdigital-testebackend-bruno (para windows)
3. Instalar todas as dependências utilizando npm install dependencies, e recomendo instalar o nodemon, utilizando npm install nodemon
4. Após isso rodar a aplicação utilizando nodemon src/index.js

# ARQUITETURA REST 

A seguir está uma configuração genérica de local host na porta 3000:

- Listagem de planetas - GET: http://localhost:3000/b2w/planetas/
- Adicionar planeta - POST: http://localhost:3000/b2w/planetas/adicionar (necessita de nome, clima e terreno, o número de aparições é automaticamente preenchido ao consumir a api swapi)
- Buscar planeta por Id - GET: http://localhost:3000/b2w/planetas/id/{inserir-id-aqui}
- Buscar planeta por Nome - GET: http://localhost:3000/b2w/planetas/nome/{inserir-nome-aqui}
- Deletar um planeta por Id - DELETE: http://localhost:3000/b2w/planetas/id/deletar/{inserir-id-aqui}
