Arrays - Parte 1
===

Mateus Chagas Sousa
github.com/matchs

---
# Array

```
Um conjunto de coisas indexado por um número
```

---
# OK, travei no indexado...
![](https://images.gr-assets.com/hostedimages/1380222758ra/425207.gif)

---
# Indexado...
Quer dizer, organizado com um índice.
Basta pensar no número da página de um livro. Aquilo é um índice que te ajuda e encontrar o conteúdo que você procura.

--

![](https://media.giphy.com/media/UrdhOc8aCtc2s/giphy.gif)

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

É possível fazer operações sobre arrays. Algumasdas  operações possíveis são:
- push
- map
- filter
- reduce

Para executar uma operação sobre um array é necessário chamar: `array` `.` `operação`

***Exemplo:***
```javascript
array.push(...);
array.map(...);
array.filter(...);
array.reduce(...);
```
---
# .push

O operador `push` serve para adicionar um novo elemento a um array

***Exemplo:***
```
var x = [1,2];

x.push(3);

console.log(x);//[1,2,3]
```

---
# .map
	
O operador `map` server para transformar um array em outro array com o mesmo número de elementos.
O `map` recebe uma função que vai ser aplicada sobre cada um dos elementos.

![](https://media.giphy.com/media/3o72F5xIDp76AZifBe/giphy.gif)

---
# Exemplo de map
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
# .filter

O operador `filter` ***filtra*** elementos indesejados de um array
O `filter` recebe uma função que vai ser aplicada sobre cada elemento e deve retornar `true` ou `false`.

![](https://media.giphy.com/media/11O6jj01F5GjDy/giphy.gif)

---
# Exemplo de `filter`
```javascript
[1,2,30,40].filter(function(e) {
    return e < 10;
});

// [1, 2]
```
---
# Exercício #3

***15 minutos***
```
Escreva uma função que receba um array de números 
e retorne um array somente com números pares
```
---
# Solução Exercício #3
```javascript
function somentePares(arr) {
    var resultado = arr.filter(function(e) {
    	var ehPar = e % 2 == 0;
    	return ehPar;
    });
    
    return resultado;
}
```
---

O operador .reduce será dado ao final, se tivermos tempo, mas fica de exercício para pesquisar em casa!
===