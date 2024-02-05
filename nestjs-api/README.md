# Imersão Full Stack & FullCycle - Ecommerce

## Descrição

Repositório da API feita com Nest.js (api de ordens de compra)

## Rodar a aplicação

** Requisitos: **

- Docker
- Docker Compose
- Node.js


Execute o comando para subir o banco de dados e rabbitmq:

```
docker compose up
```

Em outro terminal execute os comandos para subir a aplicação:

```
npm install
npm run fixture
npm run start:dev
```

Existe um arquivo `api.http` na raiz do projeto que pode ser utilizado para testar a API via extensão `Rest Client` do VSCode.

---
Tem dúvidas de como configurar seu ambiente de desenvolvimento? Veja o vídeo: [https://www.youtube.com/watch?v=O33trWxqVC4](https://www.youtube.com/watch?v=O33trWxqVC4)
---

