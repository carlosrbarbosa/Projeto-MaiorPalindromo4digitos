# Encontrando o Maior Palíndromo de Dois Números com 4 Dígitos

Este é um projeto simples em JavaScript que encontra o maior palíndromo resultante do produto de dois números com 4 dígitos.

## Contexto

Este código foi desenvolvido como parte de um processo seletivo, onde os parâmetros foram definidos da seguinte forma:

**Desafio:** Encontrar o maior palíndromo resultante do produto de dois números com 4 dígitos.

## Lógica do Código

### Geração dos Pares de Números:

O código começa com dois loops aninhados, onde `i` e `j` variam de 1000 a 9999. Estes loops garantem que todas as combinações de pares de números com 4 dígitos sejam consideradas.

### Cálculo do Produto e Verificação do Palíndromo:

Para cada par de números (`i` e `j`), o código calcula o produto `i * j`. Em seguida, utiliza a função `ehPalindromo(num)` para verificar se o produto é um palíndromo. A função `ehPalindromo(num)` converte o número em uma string, inverte a string e a compara com o número original. Se forem iguais, o número é um palíndromo.

### Atualização do Maior Palíndromo:

Se o produto é um palíndromo e maior do que o `maiorPalindromo` atual, o código atualiza o `maiorPalindromo` com o valor do produto. Isso garante que o maior palíndromo possível dos produtos dos números com 4 dígitos seja encontrado.

