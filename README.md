Equipe 3 - Participantes:
Daniel 🔗 mrdanp07
Janderson 🔗 jarderson4lmeida
Cesar 🔗 CesarMouraDev
Hermes 🔗 HermesWebDeveloper
Caio  🔗 caioviniciuus
Escopo do projeto
Para a implementação deste projeto vamo precisar usar as seguintes tecnologias:

Node.js para fornecer a possibilidade de executar JS em um servidor
Express.js para criar rotas de api
Dotenv para criarmos configurações com mais facilidade e segurança
Nodemon para termos mais produtividade em nosso ambiente de desenvolvimento
MySQL para persistência de dados
Sequelize para termos mais produtividade ao lidar com o banco de dados
JWT para adicionar segurança e limitar o acesso nas rotas de API
JEST para nos ajudar a testar e manter a qualidade do código
Estrutura de diretório
project-root/
├── src/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── app.js
│   └── server.js
├── tests/
├── .env
├── .gitignore
└── package.json
Response status code
200 OK
Indica que a API REST executou com êxito qualquer ação solicitada pelo cliente
Ao contrário do código de status 204, uma 200 deve incluir um corpo de resposta
201 CREATED
Indica que a requisição foi bem sucedida e que um novo recurso foi criado
204 No content
O código de status 204 geralmente é enviado em resposta a uma solicitação PUT ou DELETE quando a API se recusa a retornar qualquer corpo de mensagem no response
A resposta 204 NÃO DEVE incluir um corpo de mensagem
400 Bad Request
Indica que o servidor não pode ou não irá processar a requisição devido a alguma coisa que foi entendida como um erro do cliente
401 Unauthorized
Indica que a solicitação não foi aplicada porque não possui credenciais de autenticação válidas para o recurso de destino
404 Not Found
Indica que o servidor não conseguiu encontrar o recurso solicitado
Seção 01 - Implementar o banco de dados da aplicação
Requisito 01 - Criar a tabela de usuários
Requisito 02 - Criar a tabela de categorias
Requisito 03 - Criar a tabela de produtos
Requisito 04 - Criar a tabela de imagens do produto
Requisito 05 - Criar a tabela de opções do produto
Requisito 06 - Criar a tabela de produtos e categoria
Seção 02 - Implementar endpoints para o CRUD de usuarios
Requisito 01 - Criar endpoint para obter informações do usuário pelo ID
Requisito 02 - Criar endpoint de cadastro de usuário
Requisito 04 - Criar endpoint atualizar usuário
Requisito 05 - Criar endpoint de deletar usuário
Seção 03 - Implementar endpoints para o CRUD de categorias
Requisito 01 - Criar endpoint para obter uma lista de categorias
Requisito 02 - Criar endpoint para obter informações da categoria pelo ID
Requisito 03 - Criar endpoint de cadastro de categoria
Requisito 04 - Criar endpoint de atualização de categoria
Requisito 05 - Criar endpoint de deletar categoria
Seção 04 - Implementar endpoints para o CRUD de produtos
Requisito 01 - Criar endpoint para obter uma lista de produtos
Requisito 02 - Criar endpoint para obter informações do produto pelo ID
Requisito 03 - Criar endpoint de criação de produto
Requisito 04 - Criar endpoint de atualização de produto
Requisito 05 - Criar endpoint de atualização de produto
Seção 05 - Implementar e validar token JWT
Requisito 01 - Criar endpoint de geração do token JWT
Requisito 02 - Validar token nos métodos POST, PUT e DELETE
