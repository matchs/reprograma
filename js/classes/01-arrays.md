Arrays - Parte 1
===

Mateus Chagas Sousa
github.com/matchs

---
# Array

```
Um conjunto de coisas indexado por um número
```
--

### Indexado?
Isso quer dizer, organizado com um índice.
Basta pensar no número da página de um livro. Aquilo é um índice que te ajuda e encontrar o conteúdo que você procura.

---
# Como funciona um array:

Um array é aberto por um `[` e um conjunto de zero ou mais items separados por `,` e fechadocom um `]`. 

--

#### Exemplo:
```javascript
var vazio = [];

var numeros = [10, 20, 30, 40, 50];

var frutas = ['banana', 'maçã', 'pêra', 'uva'];
```

---

# Posições

Imaginando que um array é como um livro vazio, vamos dizer que cada página é uma `posição` do array. E podemos colocar o conteúdo que quisermos nas posições do array.


Ao contrário de um livro, as *"páginas"* do array começam a ser contadas de `0`.


#### Exemplo:

```javascript
var n = [5, 10, 9];

console.log(n[0]); // 5
console.log(n[1]); // 10
console.log(n[2]); // 9
```

---
# Exercício #1

***5 minutos***
```
Escreva uma função que receba um array de 4 posições 
e retorne um array com os elementos multiplicados por 2
```

***Exemplo:***
Entrada: [1, 4, 2, 5]
Saída: [2, 8, 4, 10]

---
# Solução do Exercício #1
```javascript
function somaArray(array) {
	return array[0] + array[1] + array[2] 
    				+ array[3] + array[4];
}

```

---
# Exercício #2

***30 segundos***
```
Escreva uma função que receba um array de N posições 
e retorne um array com os elementos multiplicados por 2
```

---
# Operações com arrays

É possível fazer operações sobre arrays. As operações possíveis são:
- map
- filter
- reduce

Para executar uma operação sobre um array é necessário chamar: `array` `.` `operação`

***Exemplo:***
```javascript
array.map(...);
array.filter(...);
array.reduce(...);
```

---
# .map

O operador `map` server para transformar um array em outro array com o mesmo número de elementos.

O `map` recebe um função que vai ser aplicada sobre cada um dos elementos.

***Exemplo*:**
```javascript
[1, 2, 3, 4].map(function(e) {
	return e + 2;
});

// [2, 4, 5, 6]
```
---
# Agora você consegue fazer o Exercício #2?

---
# Solução para o Exercício #2
```javascript
function multiplicaPor2(arr) {
    var resultado = arr.map(function(e) {
    	return e * 2;
    });
    
    return resultado;
}
```

---
# .reduce
---
# .filter
---