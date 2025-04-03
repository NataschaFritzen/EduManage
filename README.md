📚 **EduManage - API RESTful para Gerenciamento Educacional**

📌 **Descrição**

Este projeto é uma API desenvolvida em Node.js com Express e Sequelize, que permite a manipulação de dados através de um CRUD (Criar, Ler, Atualizar e Deletar). O sistema está configurado para utilizar SQLite como banco de dados, visualizado através da extensão SQLite Viewer no VS Code.

🚀 **Tecnologias Utilizadas**

Node.js

Express.js

Postman para testes de API

SQLite 3 e SQLite Viewer para visualizar o banco no VS Code

🛠️ **Configuração e Instalação**

1️⃣ Clonar o repositório:
https://github.com/NataschaFritzen/EduManage.git

2️⃣ Instalar dependências:
npm install

3️⃣ Configurar o banco de dados (SQLite):

Foi baixado o SQLite 3 para armazenar os dados localmente.

A extensão SQLite Viewer foi instalada no VS Code para facilitar a visualização do banco.

Verifique se o arquivo database.sqlite está na pasta database/.

Execute as migrações para criar as tabelas: npx sequelize-cli db:migrate

4️⃣ Iniciar o servidor:
npm run dev

Se tudo estiver correto, a API estará rodando em:
🔗 http://localhost:3000

🔗 **Endpoints da API (Testáveis no Postman)**

🔹 Listar Pessoas: GET.http://localhost:3000/pessoas

🔹Pessoa por id: GET.http://localhost:3000/pessoas/:id

🔹Cancela matricula: PUT. http://localhost:3000/pessoas/:id/cancela

Estas são apenas algumas das rotas principais. Para conferir todas as rotas configuradas no projeto, acesse a pasta Routes. Lá, você encontrará todos os arquivos responsáveis pelo mapeamento completo das rotas da aplicação

📄 **Licença**

Este projeto foi desenvolvido durante o curso de ORM com Node.js.



