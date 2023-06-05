# Labook Backend

Este é o projeto Labook, uma rede social com o objetivo de promover a conexão e interação entre pessoas. Desenvolvido como parte do projeto final do curso de Desenvolvimento Full Stack da Labenu, unicamente para fins didáticos.

## Sobre o Projeto

O Labook é uma rede social com o objetivo de promover a conexão e interação entre pessoas. Quem se cadastrar no aplicativo poderá criar e curtir publicações.

## Funcionalidades

O backend do LabEcommerce possui as seguintes funcionalidades:

- CRUD (Create, Read, Update, Delete) de usuários e posts
- Validação dos endpoints

## Endpoints

A API possui os seguintes endpoints disponíveis:

- **POST /users/signup**: Realiza o cadastro do usuário e fornece um token JWT.
- **POST /users/login**: Faz o login e fornece um token JWT.

- **POST /posts**: Cria um novo post.
- **GET /posts**: Retorna uma lista com todos os posts.
- **PUT /posts/:id**: Atualiza um post específico com base no seu Id. 
- **DELETE /posts/:id**: Exclui um post específico com base no seu Id.
- **PUT /posts/:id/like**: Realiza a função de like em um post específico com base no seu Id.

## Configuração do Projeto

Para configurar o projeto em sua máquina local, siga os passos abaixo:

1. Clone o repositório:

```bash
git clone https://github.com/FelipeG-Almeida/projeto-labook-backend.git

```

2. Instale as dependências do projeto:

```bash
cd projeto-labook-backend
npm install
```

3. Inicie o servidor:

```bash
npm dev start
```

O servidor será iniciado na porta especificada na variável de ambiente `PORT` (padrão: 3001).

## Documentação da API

A documentação da API pode ser encontrada em https://documenter.getpostman.com/view/24823235/2s93sXca7Y, que fornece detalhes sobre os endpoints disponíveis, parâmetros de entrada, exemplos de solicitações e respostas.

## Tecnologias e Metodologias Utilizadas

- NodeJS
- Typescript
- Express
- SQL e SQLite
- Knex
- POO
- Arquitetura em camadas
- Geração de UUID
- Geração de hashes
- Autenticação e autorização
- Roteamento
- Postman

## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir com o projeto, sinta-se à vontade para abrir uma nova issue ou enviar um pull request.
