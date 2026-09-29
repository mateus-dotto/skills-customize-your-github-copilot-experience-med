# 📘 Assignment: Consuming External APIs with JavaScript

## 🎯 Objective

Construa uma página web usando JavaScript puro para consumir uma API externa, interpretar respostas JSON e apresentar os dados ao usuário com estados de carregamento e tratamento de erros, sem instalar dependências.

## 📝 Tasks

### 🛠️ Fazer uma Requisição com Fetch

#### Descrição
Crie uma página que busque dados de uma API pública usando a API nativa `fetch()` e mostre o resultado no console do navegador.

#### Requisitos
O programa concluído deve:

- Usar `fetch()` para fazer uma requisição `GET` a uma API pública.
- Converter a resposta para JSON usando `response.json()`.
- Exibir no console um dado obtido da resposta.
- Verificar `response.ok` antes de processar a resposta.
- Funcionar sem bibliotecas ou frameworks externos.

### 🛠️ Exibir Dados na Página

#### Descrição
Aprimore a página para exibir uma lista de recursos retornados pela API, permitindo que o usuário solicite os dados por meio de um botão.

#### Requisitos
O programa concluído deve:

- Possuir um botão para iniciar a requisição.
- Renderizar pelo menos três campos dos objetos retornados pela API.
- Criar os elementos da lista com JavaScript e inseri-los no DOM.
- Limpar os resultados anteriores antes de uma nova requisição.
- Informar visualmente quando os dados forem carregados com sucesso.

### 🛠️ Tratar Carregamento e Erros

#### Descrição
Finalize a aplicação adicionando estados claros para carregamento, respostas vazias e falhas de rede ou da API.

#### Requisitos
O programa concluído deve:

- Exibir uma mensagem enquanto a requisição estiver em andamento.
- Exibir uma mensagem de erro quando a requisição falhar ou `response.ok` for `false`.
- Ocultar ou substituir a mensagem de carregamento quando a requisição terminar.
- Informar quando a resposta não contiver recursos para exibir.
- Manter a interface utilizável após uma falha e permitir uma nova tentativa.
