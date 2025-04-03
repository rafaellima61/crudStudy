Aqui está um exemplo de README para o seu projeto CRUD feito em Spring Boot:

```markdown
# CRUD Study

Este é um projeto de estudo de um CRUD (Create, Read, Update, Delete) desenvolvido com Spring Boot.

## Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Data JPA
- H2 Database

## Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/rafaellima61/crudStudy.git
   cd crudStudy
   ```

2. **Compile e execute o projeto:**
   ```bash
   ./mvnw spring-boot:run
   ```

3. **Acesse a aplicação:**
   A aplicação estará disponível em `http://localhost:8080`.

## Endpoints da API

A API expõe os seguintes endpoints:

### Criar novo item
- **URL:** `/items`
- **Método:** `POST`
- **Corpo da Requisição:**
  ```json
  {
    "name": "Item Name",
    "description": "Item Description"
  }
  ```

### Listar todos os itens
- **URL:** `/items`
- **Método:** `GET`

### Buscar item por ID
- **URL:** `/items/{id}`
- **Método:** `GET`

### Atualizar item
- **URL:** `/items/{id}`
- **Método:** `PUT`
- **Corpo da Requisição:**
  ```json
  {
    "name": "Updated Item Name",
    "description": "Updated Item Description"
  }
  ```

### Deletar item
- **URL:** `/items/{id}`
- **Método:** `DELETE`

## Banco de Dados

O projeto utiliza o banco de dados H2 para propósitos de desenvolvimento e teste. Para acessar o console do H2, utilize a URL `http://localhost:8080/h2-console` e configure as seguintes propriedades:

- **JDBC URL:** `jdbc:h2:mem:testdb`
- **User Name:** `sa`
- **Password:** (deixe em branco)

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

```
