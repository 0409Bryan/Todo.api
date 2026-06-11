# 📝 To-Do API

Projeto de uma API RESTful para gerenciamento de listas de tarefas (To-Do List), desenvolvido para a disciplina de Desenvolvimento Back-End.

## 🚀 Tecnologias Utilizadas
* **Node.js**: Ambiente de execução Javascript.
* **Express**: Framework minimalista para criação de rotas e servidores HTTP.

## 🛠️ Como Funciona a API
A API possui as seguintes rotas configuradas:

* `GET /` : Mensagem de boas-vindas e teste de status da API.
* `GET /tarefas` : Retorna a lista de todas as tarefas cadastradas.
* `POST /tarefas` : Cria uma nova tarefa (necessário enviar o `titulo` no corpo da requisição).
* `DELETE /tarefas/:id` : Remove uma tarefa específica com base no ID enviado na URL.

## 🧑‍💻 Desenvolvedor
* Desenvolvido por: [Bryan celso caetano da silva]
