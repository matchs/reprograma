Lógica de programação - JavaScript
===

## Exercícios - Múltiplos


Mateus Chagas Sousa
github.com/matchs

---
# Mútiplos

```
Escreva uma função que receba um array de números e
retorn um array com arrays de todos os números múltiplos
de 2 daquele número menores ou iguais a ele.
```

--
***Exemplo:***
```javascript
var entrada = [2, 10, 3];

multiplos(entrada); // [[0,2], [0,2,4,6,8,10], [0]]

```
---
# Dica

Para verificar se um número é mútiplo de 2 basta fazer:
```
n % 2 == 0
```