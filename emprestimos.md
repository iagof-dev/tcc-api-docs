---
description: /emprestimos/
---

# 🎫 Emprestimos

## GET

/listar/ - Listar todos

/listar/rm/<mark style="color:yellow;">\[RM]</mark> - Listar todos livros emprestados por aluno

/listar/livro/<mark style="color:yellow;">\[ID]</mark> - Listar todos emprestimos por <mark style="color:yellow;">id do livro</mark>

/listar/pendentes - Listar livros pendentes que foram emprestado, mas ainda não está no prazo de devolução.

/listar/atrasados - Listar livros que passaram do prazo de devolução e não teve prazo estendido

/listar/restituidos - Listar livros que já foram devolvidos

/listar/perdidos - Listar livros perdidos

Resultado:

```
{
  "status": "success",
  "DATA": [
    {
      "id": 17,
      "aluno_rm": 221001,
      "aluno_nome": "João Silva",
      "livro_id": 1,
      "livro_titulo": "Aprendendo SQL",
      "autor_id": 2,
      "autor_nome": "Clarice Lispector",
      "data_aluguel": "2024-08-01",
      "avaliacao_id": 17,
      "prazo": 2,
      "estado": "perdido",
      "renovavel": 1,
      "avaliacao": -1
    },
    {
      "id": 1,
      "aluno_rm": 221002,
      "aluno_nome": "Maria Santos",
      "livro_id": 1,
      "livro_titulo": "Aprendendo SQL",
      "autor_id": 2,
      "autor_nome": "Clarice Lispector",
      "data_aluguel": "2023-04-01",
      "avaliacao_id": 18,
      "prazo": 14,
      "estado": "pendente",
      "renovavel": 1,
      "avaliacao": -1
    },
    {
      "id": 24,
      "aluno_rm": 221002,
      "aluno_nome": "Maria Santos",
      "livro_id": 1,
      "livro_titulo": "Aprendendo SQL",
      "autor_id": 2,
      "autor_nome": "Clarice Lispector",
      "data_aluguel": "2025-12-31",
      "avaliacao_id": 19,
      "prazo": 14,
      "estado": "pendente",
      "renovavel": 1,
      "avaliacao": -1
    },
    {
      "id": 25,
      "aluno_rm": 221001,
      "aluno_nome": "João Silva",
      "livro_id": 51,
      "livro_titulo": "1984",
      "autor_id": 1,
      "autor_nome": "Carlos Drummond",
      "data_aluguel": "2024-08-05",
      "avaliacao_id": 20,
      "prazo": 2,
      "estado": "pendente",
      "renovavel": 1,
      "avaliacao": -1
    },
    {
      "id": 26,
      "aluno_rm": 221001,
      "aluno_nome": "João Silva",
      "livro_id": 1,
      "livro_titulo": "Aprendendo SQL",
      "autor_id": 2,
      "autor_nome": "Clarice Lispector",
      "data_aluguel": "2024-08-05",
      "avaliacao_id": 21,
      "prazo": 3,
      "estado": "pendente",
      "renovavel": 1,
      "avaliacao": -1
    }
  ]
}
```

## POST

/registrar/ - Criar um emprestimo \[RM<mark style="color:red;">\*</mark>, ID\_LIVRO<mark style="color:red;">\*</mark>, DATA\_ALUGUEL<mark style="color:red;">\*</mark>, ID\_STATUS\_EMPRESTIMO<mark style="color:red;">\*</mark>, PRAZO<mark style="color:red;">\*</mark>]

/modificar/ - Modificar estado do emprestimo \[ID<mark style="color:red;">\*</mark>,ID\_ESTADO<mark style="color:red;">\*</mark>]

/estender/ - Estender prazo de devolução \[ID\_EMPRESTIMO<mark style="color:red;">\*</mark>, novo\_prazo<mark style="color:red;">\*</mark>]
