# Capítulo 1 ignite

Este é um projeto simples de gerenciamento de tarefas, onde você pode realizar operações como criar, listar, atualizar, marcar como concluída e deletar tarefas. O backend do projeto é construído usando Node.js e as rotas são gerenciadas manualmente com expressões regulares para a correspondência de URLs. Os testes são realizados com Jest e Supertest.

## Funcionalidades

- **GET /tasks**: Retorna uma lista de todas as tarefas.
- **POST /tasks**: Cria uma nova tarefa.
- **PUT /tasks/:id**: Atualiza uma tarefa existente.
- **PATCH /tasks/:id/complete**: Marca uma tarefa como concluída.
- **DELETE /tasks/:id**: Deleta uma tarefa.

## Como Rodar

1. Clone este repositório:
   ```bash
   git clone https://github.com/mateusmaiamaia/ch1_ignite.git
   ```
2. Instale as dependências:
```bash
   npm install
```
3. Execute o servidor:
```bash
    npm start
```

