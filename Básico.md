# Meus Estudos de JavaScript Básicos 🚀

Este repositório contém exemplos fundamentais de JavaScript para prática e referência rápida de sintaxe.

---

## 1. Operações Matemáticas
Este script demonstra como declarar variáveis e realizar cálculos aritméticos básicos.

```javascript
// Declaração de variáveis numéricas
const num1 = 15;
const num2 = 5;

// Realizando operações básicas
const soma = num1 + num2;
const subtracao = num1 - num2;
const multiplicacao = num1 * num2;
const divisao = num1 / num2;

// Exibindo os resultados no console
console.log("Soma:", soma);           // Resultado: 20
console.log("Subtração:", subtracao); // Resultado: 10
console.log("Multiplicação:", multiplicacao); // Resultado: 75
console.log("Divisão:", divisao);     // Resultado: 3


// Definindo uma nota de aluno
const nota = 7.5;

// Verificando se a nota é suficiente para passar
if (nota >= 7) {
    // Caso a condição seja atendida
    console.log("Parabéns! Você foi aprovado.");
} else {
    // Caso a condição não seja atendida
    console.log("Estude um pouco mais, você ficou de recuperação.");
}

// Criando uma lista de linguagens de programação
const linguagens = ["JavaScript", "Python", "Java", "C++"];

console.log("Linguagens que pretendo aprender:");

// O laço 'for...of' percorre cada item da lista individualmente
for (let item of linguagens) {
    // Imprime o item atual da repetição
    console.log("-> " + item);
}

// Mostra o total de itens na lista
console.log("Total de linguagens: " + linguagens.length);
