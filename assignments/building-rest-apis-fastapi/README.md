# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Construa uma API REST usando o framework FastAPI para praticar criação de rotas, operações CRUD, validação de dados com Pydantic e uso adequado de códigos de status HTTP.

## 📝 Tasks

### 🛠️ Criar a Aplicação FastAPI

#### Descrição
Configure uma aplicação FastAPI e crie uma rota de verificação para confirmar que o servidor está funcionando.

#### Requisitos
O programa concluído deve:

- Criar uma instância de `FastAPI` em um arquivo Python.
- Disponibilizar uma rota `GET /health`.
- Retornar uma resposta JSON com o status da aplicação, como `{"status": "ok"}`.
- Permitir a execução do servidor com Uvicorn.

### 🛠️ Implementar um CRUD de Tarefas

#### Descrição
Implemente uma API para cadastrar e consultar tarefas de estudo armazenadas em memória.

#### Requisitos
O programa concluído deve:

- Criar um modelo de tarefa com identificador, título e descrição.
- Implementar `POST /tasks` para criar uma tarefa.
- Implementar `GET /tasks` para listar todas as tarefas.
- Implementar `GET /tasks/{task_id}` para buscar uma tarefa pelo identificador.
- Implementar `DELETE /tasks/{task_id}` para remover uma tarefa existente.

### 🛠️ Validar Dados e Respostas HTTP

#### Descrição
Aprimore a API para validar entradas e informar corretamente o resultado de cada operação ao cliente.

#### Requisitos
O programa concluído deve:

- Rejeitar tarefas sem título usando validação do Pydantic.
- Retornar `404 Not Found` quando o identificador solicitado não existir.
- Retornar `201 Created` ao criar uma tarefa com sucesso.
- Retornar `204 No Content` ao remover uma tarefa com sucesso.
- Documentar automaticamente as rotas por meio do Swagger UI do FastAPI.
