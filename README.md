# Decolando-2025
RESTful API desafio decola tech.

## Diagrama

```mermaid
classDiagram
    class Jogo {
        id: String
        nome: String
        descricao: String
        URL_da_imagem: String
    }

    class Console {
        consoleId: String
        nome: String
    }

    class Categoria {
        categoriaId: String
        nome: String
    }

    Jogo --* Console
    Jogo *-- Categoria
```
