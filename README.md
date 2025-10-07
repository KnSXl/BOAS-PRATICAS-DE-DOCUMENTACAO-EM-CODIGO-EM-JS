# BOAS-PRATICAS-DE-DOCUMENTACAO-EM-CODIGO-EM-JS

### EM VARIÁVEIS
```js
const x = 0; // O que é/o que faz
```

### EM FUNÇÕES
```js
/**
* O que faz.
*/
function nomeFuncao() {}

/**
* O que faz.
* @param {string} parametro - O que é.
* @returns {string} O que retorna.
*/
function nomeFuncao(parametro) {
    return parametro;
}
```

## EXEMPLOS

### EM VARIÁVEIS
```js
let contador = 0; // Número de tentativas feitas pelo usuário
```

### EM FUNÇÕES
```js
/**
 * Soma dois números e retorna o resultado.
 * @param {number} num1 - Primeiro número.
 * @param {number} num2 - Segundo número.
 * @returns {number} A soma de a e b.
 */
function somar(num1, num2) {
    return num1 + num2;
}

/**
 * Exibe uma mensagem de saudação no console.
 */
function exibirSaudacao() {
    console.log("Olá!");
}
```

## REFERÊNCIAS

* [JSDoc](https://jsdoc.app/)
