# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function soma(a, b){
  return a + b;
  }
  console.log(soma(10, 10))

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
let x = soma(1, 2) + "5";
console.log(x)

// Qual o valor atualizado dessa variável?
35

// Declare uma nova variável, sem valor.
let y 

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function adicione(y){
return "valor";
}
// Invoque a função criada acima.
console.log(adicione(y))

// Qual o retorno da função? (Use comentários de bloco).
valor
/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function tres(a, b, c){
    if(a!== undefined && b === undefined && c === undefined){
        return  a;
    }
    else if(a !== undefined && b !== undefined && c === undefined){
        return a + b;
    }
    else if(a !== undefined && b !== undefined && c !== undefined){
        return (a + b) / c;
    }   
    else if(a === undefined && b === undefined && c === undefined){
        return false;
    }else{
        return null;
    }
} 
console.log(tres(1, 2, 3) + "2")

// Invoque a função criada acima, passando só dois números como argumento.
console.log(tres(1, 2))

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
NaN //foi declarado só dois argumento

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
console.log(tres(1, 2, 3))

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
6 é multiplicaçao dos tres argumentos

console.log(tres(1, 2, 3) + "2")
?

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
NaN com um argumento
NaN com dois argumento
e o valor da multiplicaçao com os tres argumentos

```
