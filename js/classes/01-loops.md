---
title: Lógica de Programação - JavaScript - Repetições
author: Mateus Chagas Sousa [github.com/matchs](github.com/matchs)
...
# Laços, repetições 
... ou simplesmente: ***LOOPS***

`Servem para repetir um mesmo trecho de código um determinado número vezes ou até que uma condição seja atingida.`

Em JavaScript existem dois tipos principais de loops:
- ***for***
- ***while***

---
# for

```javascript
for(inicialização; condição de parada; incremento) {
    // seu código vai aqui
}
```

**Inicialização:**
Basicamente uma declaração de variável
```javascript
var i = 0;
```

**Condição de parada**
Igual do `ìf`

```javascript
i < 1000
```

**Incremento**
Aumentar ou acrescentar alguma coisa
```javascript
i = i + 1;
i++;
i+=1;
```

---
# Solução Exercício #2

```javascript
for (var i = 0; i < 1000; i++:) {
    console.log('Mateus');
}
```
