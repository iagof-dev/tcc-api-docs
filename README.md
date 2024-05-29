---
description: Lista de requests com os dados necessários.
---

# 🏠 Inicio

## ❓ Como compilar a API

```
docker compose up -d
```

## [⚠️](https://emojipedia.org/warning) Aviso

Todos os requests do método POST precisam dessa chave:

<pre><code><strong>authpass: c38a7e02bfca0da201015ce51931b09d462080b7
</strong></code></pre>

Enviado junto no campo de form-data

## 🏃 Como fazer a request

precisa juntar URL + "CATEGORIA" + METODO

#### Exemplo GET:

LISTAR TODOS - <mark style="color:blue;">url.com</mark><mark style="color:yellow;">/ALUNOS/</mark><mark style="color:red;">LISTAR</mark>

LISTAR POR RM - <mark style="color:blue;">url.com</mark><mark style="color:yellow;">/ALUNOS/</mark><mark style="color:red;">RM/</mark><mark style="color:purple;">221020</mark>
