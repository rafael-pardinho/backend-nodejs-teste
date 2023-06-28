
# Backend

Backend simples para testes


## Autores

- [@Rafael Pardinho](https://github.com/rafael-pardinho)


## Instalação dependências

Eu usei o Yarn

```bash
  yarn install

```
## Iniciando a aplicação

```bash
  yarn start

```
    
## Documentação da API


#### Retorna todos os itens

#### Metodo GET

```http
  GET /products
```



#### Retorna um item

```http
  GET /products/{id}
```
| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `number` | **Obrigatório**. O ID do item que você quer |

#### Metodo POST

```http
  POST /products
```
#### Body x-www-form-urlencoded
| Key   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `name`      | `string` | **Obrigatório**. Nome do produto |
| `price`      | `string` | **Obrigatório**. Preço do Produto |

#### Metodo DELETE

```http
  DELETE /products/{id}
```
| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `number` | **Obrigatório**. O ID do item que você quer apagar |

#### Metodo PUT

```http
  PUT /products/{id}
```
| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `number` | **Obrigatório**. O ID do item que você quer alterar |




## Apêndice

Essa é uma API REST CRUD simples para fins de testes, não tem conexão com banco de dados, os dados serão gravados no arquivo db.json.

