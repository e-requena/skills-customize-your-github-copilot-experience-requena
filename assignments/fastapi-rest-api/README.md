# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Construa uma API REST simples usando o framework FastAPI para aprender roteamento, validação com Pydantic e operações CRUD básicas.

## 📝 Tasks

### 🛠️ Implement API endpoints

#### Description

Implemente uma API para gerenciar recursos do tipo "item" usando armazenamento em memória. A API deve permitir criação, leitura, atualização e remoção de itens, validar dados de entrada e retornar códigos HTTP apropriados.

#### Requirements
Completed program should:

- Expor endpoints: `GET /items`, `GET /items/{item_id}`, `POST /items`, `PUT /items/{item_id}`, `DELETE /items/{item_id}`.
- Usar modelos Pydantic para schemas de requisição e resposta.
- Validar entrada e retornar status HTTP corretos (`400` para entrada inválida, `404` para item não encontrado).
- Utilizar armazenamento em memória (dicionário) com IDs inteiros únicos.
- Incluir um ponto de entrada `main()` para execução local com Uvicorn.
- Incluir exemplos de requisições usando `curl`.

#### Example requests

```
curl -s -X POST http://localhost:8000/items -H "Content-Type: application/json" -d '{"name":"Notebook","price":9.99}'
curl -s http://localhost:8000/items
curl -s http://localhost:8000/items/1
```
