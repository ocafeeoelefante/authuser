# AuthUser

![PHP](https://img.shields.io/badge/PHP-7.0%2B-blue)
![MySQL](https://img.shields.io/badge/MySQL-5.7%2B-red)
![XAMPP](https://img.shields.io/badge/XAMPP-7.4%2B-yellow)

Um sistema simples de autenticação de usuários em PHP. 

## Requisitos

- PHP >= 7.0
- MySQL
- Servidor web (ex: XAMPP, WAMP)

## DB

1. Crie um banco de dados chamado `authuser`.
2. Execute o comando SQL para criar a tabela `users`:

```sql
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL
);
