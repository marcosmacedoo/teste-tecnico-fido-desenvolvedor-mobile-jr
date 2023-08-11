# Teste técnico da Fido | Desenvolvedor Mobile Jr

Crie um App em React Native que tenha login, faça a busca de um CEP na API da [ViaCEP](https://viacep.com.br/), exiba o endereço retornado dela e salve-o na [nossa API](https://64d4f66fb592423e4694f420.mockapi.io/api/v1/user/). O objetivo é de utilizar a API ViaCEP para consultas e nossa API para fazer um CRUD. Faça o App baseado nesse [protótipo](https://www.figma.com/file/2823d5LCnlZVepEPD4ugNU/Teste-t%C3%A9cnico-da-Fido-%7C-Desenvolvedor-Mobile-Jr?type=design&node-id=1%3A2&mode=design&t=1PvPqnA1oMUONpIM-1). Caso queira ver o fluxo do App [clique aqui](https://www.figma.com/proto/2823d5LCnlZVepEPD4ugNU/Teste-t%C3%A9cnico-da-Fido-%7C-Desenvolvedor-Mobile-Jr?type=design&node-id=8-2&t=rdUQ5vUf5PIZrKDu-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=8%3A2&mode=design)

## Sobre nossa API
URL Base: https://64d4f66fb592423e4694f420.mockapi.io/api/v1/

#### Get all users

```http
  GET /user
```


#### Buscar dados de user

```http
  GET /user/:id
```
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

 
#### Atualizar user

```http
  PUT /user/:id
```
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

| Body          | Type     | Description                           |
| :--------     | :------- | :--------------------------------     |
| `name`        | `string` | **Not required**. Id of item to fetch |
| `password`    | `string` | **Not required**. Id of item to fetch |
| `cep`         | `string` | **Not required**. Id of item to fetch |
| `endereco`    | `string` | **Not required**. Id of item to fetch |
| `complemento` | `string` | **Not required**. Id of item to fetch |
| `numero`      | `string` | **Not required**. Id of item to fetch |
| `cidade`      | `string` | **Not required**. Id of item to fetch |
| `estados`     | `string` | **Not required**. Id of item to fetch |


#### Criar user

```http
  POST /user
```
| Body          | Type     | Description                       |
| :--------     | :------- | :-------------------------------- |
| `name`        | `string` | **Required**. Id of item to fetch |
| `password`    | `string` | **Required**. Id of item to fetch |
| `cep`         | `string` | **Required**. Id of item to fetch |
| `endereco`    | `string` | **Required**. Id of item to fetch |
| `complemento` | `string` | **Required**. Id of item to fetch |
| `numero`      | `string` | **Required**. Id of item to fetch |
| `cidade`      | `string` | **Required**. Id of item to fetch |
| `estados`     | `string` | **Required**. Id of item to fetch |


#### Realizar login

```http
  POST /login
```
| Body       | Type     | Description                       |
| :--------  | :------- | :-------------------------------- |
| `name`     | `string` | **Required**. Id of item to fetch |
| `password` | `string` | **Required**. Id of item to fetch |


## Requisitos obrigatórios
- React Native
- Axios
- Componentização
- Clean Code
- Fidelidade ao protótipo
- Git/Git Flow
- Readme explicativo
  

## Requisitos opcionais
- TypeScript
- CI/CD
- Git conventional commit
- Hooks customizados
- Testes unitários
- Gerar APK


## Prazo de entrega

Entregue até as 18:00 do dia 14/08 (Segunda-feira). Envie o link do repositório projeto.