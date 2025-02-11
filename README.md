# Rocketseat NLW Journey - Node.js

Este repositório contém o código desenvolvido durante a NLW Journey da Rocketseat, focado em Node.js.

## Funcionalidades

- **Gerenciamento de Banco de Dados**: Utiliza o Prisma para definição de esquemas e migrações, facilitando a interação com o banco de dados.

- **API RESTful**: Fornece endpoints para operações CRUD, permitindo a interação com os recursos da aplicação.

- **Autenticação e Autorização**: Implementa mecanismos de autenticação de usuários e proteção de rotas sensíveis.

- **Validação de Dados**: Garante a integridade e consistência dos dados através de validações robustas.

- **Tratamento de Erros**: Oferece respostas claras e informativas para diferentes tipos de erros que possam ocorrer.

## Tecnologias Utilizadas

- Node.js
- TypeScript
- Prisma

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/kerlenmelo/rocketseat_nlw-journey-nodejs.git
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Configure o banco de dados no arquivo `.env`.
4. Execute as migrações do Prisma:
   ```bash
   npx prisma migrate dev
   ```
5. Inicie o servidor:
   ```bash
   npm run dev
   ```
