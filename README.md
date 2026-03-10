🚀 Projeto API Rest - CRUD de Usuários
Este projeto é uma API Rest funcional desenvolvida para o gerenciamento de usuários, focada em performance e escalabilidade.

🛠️ Tecnologias Utilizadas
O projeto foi construído com as seguintes tecnologias:

Node.js: 
Express 
JavaScript
MongoDB
Prisma ORM

⚙️ Como rodar o projeto
Se você estiver voltando a este projeto depois de um tempo, siga estes passos:

Instale as dependências:

Bash
npm install
Configure as variáveis de ambiente:
Crie um arquivo .env na raiz do projeto e adicione a sua URL de conexão do MongoDB:

Snippet de código
DATABASE_URL="mongodb+srv://seu_usuario:sua_senha@cluster.mongodb.net/nome_do_banco"
Sincronize o Prisma:

Bash
npx prisma generate
Inicie o servidor:

Bash
node server.js
