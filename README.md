# Operadores em JavaScript

    Aprendendo a usar os operadores na linguagem javascript

# aritmeticos.js

Inicialmente, calculamos a idade de Renatha com variáveis declaradas com `const`

~~~js
const anoAtual = 2024 
const anoNascimento = 1997
~~~

Depois, declaramos variáveis `const` para fazer cálculos

~~~~js
const numero1 = 30
const numero2 = 20
~~

Realizamos as operações utilizando esses operadores aritméticos:

*`+`
*`-`
*`*`
*`%`
*`/`

As operações são realizadas no momento da impressão do resultado e não precisam ser armazenadas em variáveis

## operadores-atribuicao.js

~~~js
let numero = 10
~~~

Declaramos a variável `número` usando a palavra reservada `let`, pois essa variável será reatribuída ao longo do nosso código.

~~~js
console.log(`O número inicial é ${numero}`)
console.log(`Somando 10: ${numero += 10}`)
console.log(`Subtraindo 10: ${numero -= 10}`)
console.log(`Multiplicando 10: ${numero *= 10}`)
console.log(`Dividindo 10: ${numero /= 10}`)
console.log(`Elevando a potência 10: ${numero *= 10}`)
console.log(`Obtendo o resto da divisão por 10: ${numero %= 10}`)
console.log(`Incrementando 1: ${++numero}`)
console.log(`Decrementando 1: ${numero--}`)
console.log(`O número final é: ${numero}`)
~~~

Operadores de atribuição:

* `+=` -> O próprio valor somado ao novo valor
* `-=` -> O próprio valor subtraindo-se ao novo valor
* `*=` -> O próprio valor multiplicado pelo novo valor
* `/=` -> O próprio valor dividido pelo novo valor
* `**=` -> O próprio valor elevado a potência do novo valor 
* `%=` -> O resto da divisão do próprio valor pelo novo valor
* `++` -> O próprio valor **incrementado (somado) com 1** (pode ser um _pré-incremento_ ou _pós-incremento_).
* `--` -> O próprio valor **decrementado (subtraído) com 1** (pode ser um _pré-decremento_ ou _pós-decremento_).
