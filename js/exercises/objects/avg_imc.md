Lógica de programação - JavaScript
===

## Exercícios - Média IMC


Mateus Chagas Sousa
github.com/matchs

---

# Média IMC

```
Escreva uma função que, dado um conjunto 
de pesos (em kg) e alturas (em metros) 
escreva a média dos IMCs.
```

---
# Formato da entrada:

```javascript
[ 
    { peso: xx, altura: xx }, 
    ... 
]
```
---
# Exemplo de uso: 

```javascript
var entrada = [
    {
    	peso: 75.5,
        altura: 1.80
    },
    {
    	peso: 90.0,
        altura: 2.10
    },
    {
    	peso: 100,
        altura: 1.60
    },
];

var resultado = mediaIMC(entrada);
console.log(resultado);
```