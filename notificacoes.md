---
description: /notificacoes/
---

# 🔔 Notificacões

## GET

/listar/ - Listar todas notificações

/listar/rm/<mark style="color:purple;">\[RM]</mark> - Listar notificações por rm

/listar/telefone/<mark style="color:purple;">\[NUMERO]</mark> - Listar notificações por n° telefone

Resultado:

```
{
  "status": "success",
  "DATA": [
    {
      "id": 1,
      "rm_aluno": 2210002,
      "data_envio": "2023-04-16 00:00:00",
      "iteracao": 1,
      "data_aluguel": "2023-04-01",
      "data_devolucao": "2023-04-15",
      "prazo": 14,
      "codigo": "L001",
      "titulo": "Aprendendo SQL",
      "aluno_nome": "Maria Santos",
      "telefone": "23456789012",
      "estado": "pendente",
      "curso": "Informatica"
    }
  ]
}
```

## POST

/registrar/ - Registrar notificação \[id\_aluno<mark style="color:red;">\*</mark>,id\_emprestimo<mark style="color:red;">\*</mark>,data\_envio<mark style="color:red;">\*</mark>,iteracao<mark style="color:red;">\*</mark>]

