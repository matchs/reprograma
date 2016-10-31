Lógica de programação - JavaScript
===

## Exercícios - Xadrez


Mateus Chagas Sousa
github.com/matchs

---
# Xadrez

```
Um tabuleiro de xadrez é composto de 64 casas 
num arranjo de 8 linhas e 8 colunas. 

Dessas 32 são pretas e 32 são brancas. 
Sendo que a casa no canto inferior esquerdo 
é sempre branca.

As peças do Xadrez são distribuídas inicialmente 
da seguinte maneira (da esquerda para a direita):
Na primeira linha: 
    Torre (T), 
    Cavalo (C), 
    Bispo (B), 
    Rainha (R), 
    Rei (K), 
    Bispo (B), 
    Cavalo (C), 
    Torre (T).
    
Na segunda linha:
    8 peões (P)
```

---
# Exercício

```
Escreva uma função que desenhe um tabuleiro de xadrez
utilizando:
    `#` para casas pretas
    `_` para casas brancas

E com as peças distribuídas no tabuleiro 
para um dos jogadores.

Antes de cada linha deve ser exibido o número da linha.
```
---
# Exemplo:
```javascript
1. T C B R K B C T
2. P P P P P P P P
3. # _ # _ # _ # _
4. _ # _ # _ # _ #
5. # _ # _ # _ # _
6. _ # _ # _ # _ #
7. # _ # _ # _ # _
8. _ # _ # _ # _ #
```
---
# Dica


***Para verificar se o número é múltiplo de 4:***
```javascript
x % 4 == 0
```