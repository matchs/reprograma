Lógica de programação - JavaScript
===

## Exercícios - Jogo do Pin do Silvio Santos


Mateus Chagas Sousa
github.com/matchs

---
# Jogo do PIN

```
Escreva uma função que receba um número e retorne
um array com todos menores ou iguais a este
e maiores que zero mas com a palavra "PIN" 
no lugar dos números que forem mútiplos de 4.
```

***Exemplo:***
```javascript
pin(2) // [1, 2]
pin(4) // [1, 2, 3, "PIN"]
pin(10) // [1, 2, 3, "PIN", 5, 6, 7, "PIN", 9, 10]
```
---
# Dica


***Para verificar se o número é múltiplo de 4:***
```javascript
x % 4 == 0
```