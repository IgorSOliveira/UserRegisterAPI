# UserRegisterAPI
Este projeto é uma API construída utilizando Java, Spring Boot e MySQL como banco de dados.

## API endpoints:
Esta Api oferece os seguintes endpoints:

*GET USERS*
```markdown
GET /users - Retorna a lista com todos os usuários.
```
```json
[
    {
        "id": 1,
        "username": "Igor"
        "email": "igor@example.com",
        "password": "123",
    },
    {
        "id": 4,
        "username": "Pedro"
        "email": "pedro@example.com",
        "password": "455",
    }
]
```
*POST USERS*
```markdown
POST /users - Registra um novo usuário no banco.
```
```json
[
    {
        "username": "Marcos"
        "email": "marcos@example.com",
        "password": "123",
    },
]
```
