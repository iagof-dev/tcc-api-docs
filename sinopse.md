---
description: /sinopse/
---

# 📑 Sinopse

## POST

/gerar/ - Gerar uma sinopse de um livro por Inteligencia Artificial

Campos necessários: \[Livro<mark style="color:red;">\*</mark>, Autor<mark style="color:red;">\*</mark>, Caracteres<mark style="color:red;">\*</mark>]

Resultado:

```
{
  "status": "success",
  "ai_model": "gemini-1.5-flash-latest",
  "message": "Greg Heffley, um garoto de 12 anos, narra seu cotidiano em um diário cheio de peripécias. Do primeiro dia de aula a desafios com amigos e família, Greg tenta sobreviver à adolescência e se tornar popular, enfrentando situações hilárias e constrangedoras. Através de desenhos e textos engraçados, o leitor acompanha as aventuras de Greg e suas tentativas de se encaixar no mundo.\n",
  "index": 0,
  "total-used-tokens": 201
}
```
