# Docker Todo List

Este projeto é uma aplicação de lista de tarefas (Todo List) desenvolvida para praticar conceitos de Docker, Node.js e React.

## Estrutura do Projeto

- `docker/todo-app/back-end/`: API Node.js para gerenciamento das tarefas.
- `docker/todo-app/front-end/`: Interface web em React para interação com as tarefas.
- `docker/todo-app/tests/`: Testes automatizados end-to-end.
- `docker/docker-commands/`: Exemplos de comandos Docker.
- `docker/docker-compose.yml.example`: Exemplo de configuração Docker Compose.

## Como executar

1. **Back-end**

   - Entre na pasta `docker/todo-app/back-end/`
   - Execute `npm install` (se necessário)
   - Execute `npm start` para iniciar a API na porta 3001

2. **Front-end**

   - Entre na pasta `docker/todo-app/front-end/`
   - Execute `npm install` (se necessário)
   - Execute `npm start` para iniciar o front-end na porta 3000

3. **Com Docker**
   - Utilize os comandos do diretório `docker/docker-commands/` para criar imagens e containers.
   - Edite e utilize o arquivo `docker/docker-compose.yml.example` para orquestrar os serviços.

## Testes

- Os testes automatizados estão em `docker/todo-app/tests/`.
- Para rodar os testes, siga as instruções do arquivo `package.json` dessa pasta.
