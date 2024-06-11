---
description: /livros/
---

# 📘 Livros

## GET

/listar/ - Lista todos os livros

/listar/codigo/<mark style="color:purple;">\[CÓDIGO]</mark> - Listar livro por código

/listar/genero/<mark style="color:purple;">\[ID\_GENERO]</mark> - Listar livro por genero

\-/listar/titulo/<mark style="color:purple;">\[VALOR]</mark> - Listar livro por titulo (Autocompletar)

\-/listar/autor/<mark style="color:purple;">\[VALOR]</mark> - Listar livro por autor (Autocompletar)

Resultado:

```
{
  "status": "success",
  "DATA": [
    {
      "id": 1,
      "codigo": "L001",
      "titulo": "Aprendendo SQL",
      "capa": "https://m.media-amazon.com/images/I/811EGiSqCPL._AC_UF1000,1000_QL80_.jpg",
      "sinopse": "Um guia completo para aprender SQL do zero.",
      "volumes": 1,
      "autor": "Carlos Drummond",
      "editora": "Editora Alpha",
      "genero": "Educação",
      "avaliacao": 3.83333333333333
    },
    {
      "id": 1,
      "codigo": "L001",
      "titulo": "Aprendendo SQL",
      "capa": "https://m.media-amazon.com/images/I/811EGiSqCPL._AC_UF1000,1000_QL80_.jpg",
      "sinopse": "Um guia completo para aprender SQL do zero.",
      "volumes": 1,
      "autor": "Carlos Drummond",
      "editora": "Editora Alpha",
      "genero": "Tecnologia",
      "avaliacao": 3.83333333333333
    },
    {
      "id": 2,
      "codigo": "L002",
      "titulo": "Programação avançada em Linux",
      "capa": "https://cdn.dlojavirtual.com/static1/102704/sku/informatica-livro-programacao-avancada-em-linux-1707774500502.jpg",
      "sinopse": "\"Programação Avançada em Linux\" é um guia abrangente e prático para desenvolvedores que desejam aprofundar seus conhecimentos no ambiente Linux. Escrito por Gleicon da Silva Moraes, um especialista renomado na área, este livro mergulha nos aspectos mais avançados da programação para Linux, oferecendo insights valiosos e técnicas essenciais para dominar a plataforma. Desde o entendimento detalhado do kernel até a implementação de sistemas distribuídos e técnicas avançadas de depuração, cada capítulo é projetado para desafiar e expandir o conhecimento do leitor, permitindo-lhes criar aplicativos robustos e eficientes para o ecossistema Linux. Com exemplos de código claros e exercícios práticos, este livro é tanto um recurso de referência essencial quanto um guia de aprendizado indispensável para qualquer desenvolvedor que deseje se destacar na programação avançada em Linux.",
      "volumes": 2,
      "autor": "Clarice Lispector",
      "editora": "Editora Beta",
      "genero": "Tecnologia",
      "avaliacao": 0
    }
  ]
}
```

## POST

/criar/ - Criar livro | \[ID, CODIGO<mark style="color:red;">\*</mark>, TITULO<mark style="color:red;">\*</mark>, ID\_AUTOR<mark style="color:red;">\*</mark>, ID\_EDITORA<mark style="color:red;">\*</mark>, CAPA<mark style="color:red;">\*</mark>, VOLUMES<mark style="color:red;">\*</mark>, SINOPSE<mark style="color:red;">\*</mark>]

/modificar/ - Modificar informações | \[ID<mark style="color:red;">\*</mark>]

/deletar/ - Deletar livro | \[ID<mark style="color:red;">\*</mark>]
