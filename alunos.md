---
description: /alunos/
---

# 👦 Alunos

## GET

/ - todos os dados.

/rm/[^1]<mark style="color:yellow;">\[RM]</mark> - dados por RM

/telefone/[^2]<mark style="color:yellow;">\[NUMERO]</mark> - dados por n° de telefone.

<mark style="color:yellow;">Resultado:</mark>

```
{
  "status": "success",
  "DATA": [
    {
      "rm": 2210001,
      "nome": "João Silva",
      "telefone": "12345678901",
      "ano": 2023,
      "curso": "Desenvolvimento de Sistemas",
      "periodo": "Integral"
    },
    {
      "rm": 2210002,
      "nome": "Maria Santos",
      "telefone": "23456789012",
      "ano": 2023,
      "curso": "Informatica",
      "periodo": "Integral"
    },
    {
      "rm": 2210003,
      "nome": "Carlos Pereira",
      "telefone": "34567890123",
      "ano": 2023,
      "curso": "Enfermagem",
      "periodo": "Noturno"
    }
  ]
}
```

## POST

/criar/ - Registrar aluno

Campos necessários: \[rm<mark style="color:red;">\*</mark>, nome<mark style="color:red;">\*</mark>, id\_curso<mark style="color:red;">\*</mark>, telefone<mark style="color:red;">\*</mark>]



[^1]: informar o valor após a barra.



[^2]: informar o valor após a barra.
