
# Título do Projeto

Uma breve descrição sobre o que esse projeto faz e para quem ele é


## Instalação

Instale my-project com npm

```bash
  npm install my-project
  cd my-project
```

## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

```bash
  API_KEY=    # Descrição - Chave da sua API
  ANOTHER_API_KEY=    # Descrição - Chave da sua API
```
    
## Documentação da API

Ela pode ser chumbada ou um link para o Swagger/Postman

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |

#### add(num1, num2)

Recebe dois números e retorna a sua soma.


## Deploy

Para fazer o deploy desse projeto rode

```bash
  npm run deploy
```

