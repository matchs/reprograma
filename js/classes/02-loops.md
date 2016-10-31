Loops - Parte 1
===

![](https://media.giphy.com/media/l3fQwP0Fv7ek6uPWU/giphy.gif)

Mateus Chagas Sousa
github.com/matchs

---
# Laços, repetições 
... ou simplesmente: ***LOOPS***

```javascript
Servem para repetir um mesmo trecho de código um 
determinado número vezes ou até que uma condição 
seja atingida.
```

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

**Inicialização:** Basicamente uma declaração de variável
```javascript
var i = 0;
```

**Condição de parada:** Igual do `ìf`

```javascript
i < 1000
```

**Incremento:** Aumentar ou acrescentar alguma coisa
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

---
# Exercício #3

***15 minutos***
```
Escreva uma função que some todos os números de 0 a 100
ou seja: 0 + 1 + 2 + ... + 100
```

---
# Solução do Exercício #3
```javascript
function somaAte100() {
	var soma = 0;
	for (var i = 0; i <= 100; i++) {
    	soma = soma + i;
    }
    
    return soma;
}
```

---
# While
```javascript
while (condicao) {
 // Faz alguma coisa
}
```

---
# Exercício #4
```
Repita o Exercício #3 mas agora utilize apenas while
```

---
# Solução do Exercício #4
```javascript
function somaAte100() {
    var i = 0;
    var soma = 0;
    while (i <= 100) {
        soma = soma + i;
        i++;
    }
}
```

---
# Qual a diferença entre `for`e `while`?

---
# Nenhuma!!!!

* A forma de pensar das duas é um pouco diferente mas o resultado é sempre o mesmo.

* Utilizar um ou outro é preferência pessoal!

---
# Dúvidas?

---
# Então vamos PRATICAR mais!!
---
