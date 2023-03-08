# JavaScript Core

- Neste curso vamos falar sobre o JavaScript Core, que é o JavaScript puro, sem nenhum framework. 
JavaScript é uma linguagem de programação que roda no navegador do usuário, 
e pode rodar no computador com algumas aplicações que serão citadas em seguida no curso. 
Com o JavaScript podemos criar aplicações web, mobile com React Native, e desktop com Electron. 
Neste curso vamos entender conceitos e fundamentos, praticaremos eles e depois revisaremos.

* Linguagem de programação que roda no Navegador do usuário (front-end)
    * Se você clicar em algum botão da página e aparece uma janela. Isso é o JavaScript
    * Alteração também no computador (back-end)

## O que podemos fazer?

* Podemos criar aplicações web, mobile (React Native), desktop (Electron)
* Empresas famosas que usam
    * Meta (Facebook, Instagram, Whatsapp)
    * Google (Youtube, Gmail, Drive)
    * Uber
    * Netflix
    * TikTok
    * ...

* 99.99% dos sites na web usam JavaScript
* Linguagem obrigatória para quem programa o Front-end Web

## Evolução

* A comunidade cresce cada vez mais e a linguagem está sempre evoluindo

## O que vamos ver no curso?

- Tipos de dados
- Variáveis
- Funções
- Condicionais
- Estrutas de repetição
- ...

## Como vai funcionara dinâmica do curso?

- Treino de futebol
- Treino de artes marciais

* Conceitos e fundamentos
* Prática
* Revisão

-------------------------------------------------------------------------------------------------------

# A importância da Sintaxe

- Nesta aula vamos entender melhor a sintaxe, que é o jeito de escrever código para ele ser entendido pela máquina, que todas as linguagens tem e que engloba 82% dos erros de iniciantes em programação.

* Toda linguagem tem Sintaxe
* Uma boa comunicação necessita de uma boa sintaxe
* 82% dos erros para iniciantes programação

```js
    console.log("Bem vindos ao Starter")
```

-------------------------------------------------------------------------------------------------------

# Maneiras de executar o JavaScript

- Nesta aula vamos citar 3 maneiras de executar códigos em JavaScript, a primeira maneira é pelo navegador, clicando na tecla F12 em qualquer website o menu do DevTools, que são ferramentas para desenvolvedores, na aba console podemos executar código JavaScript. A segunda forma é pela aplicação web CodePen, abrindo o endereço codepen.io/pen você encontra um ambiente que se pode utilizar codigo HTML, CSS e JavaScript. Também pode-se usar o Visual Studio Code, criando um arquivo HTML com a tag <script></script> e colocando o código dentro.

-------------------------------------------------------------------------------------------------------

# Adicionando arquivos JS

- Uma outra maneira de organizar o código JavaScript é criando um arquivo com um final ".js" no diretório junto ao arquivo HTML, de preferência evitando usar caracteres especiais como letras acentuadas e espaços. Para conectar este arquivo JS ao HTML, pode-se usar a linha de código <script src="./nomedoarquivo.js"></script> no body, agora abrindo este arquivo HTML o código será executado.

-------------------------------------------------------------------------------------------------------

# Comentários

- Para comentar seu código no Javascript, pode se usar // antes da linha, para definir aquela linha inteira, para comentar mais de uma linha, pode se usar um /* no começo do comentário e um */ no final. Comentários não são executados, mas são mostrados para quem visualiza o código.

-------------------------------------------------------------------------------------------------------

# Tipos de dados

- Para entendermos mais sobre os tipos de dados, podemos compará-los com elementos da gramática, para aprendermos precisamos saber como escrever, os significados e continuar aprendendo para expandir nosso vocabulário. A dinâmica do aprendizado nesse módulo vai consistir em conceitos e escrita, deixando a aplicação para um outro momento, vamos aprender os tipos de dados mais utilizados.

* Gramática
    * Elementos da linguagem e suas combinações
    * A arte de falar e escrever corretamente

* Vocabulário
    * Conjunto de termos e expressões
    * Agrupamento de palavras

* Precisamos saber como escrever
* Precisamos saber os significados
* Precisamos continuar aprendendo, para crescer nosso vocabulário.

## Como vai ser a dinâmica do aprendizado?

* Conceitos e escrita

> Vamos aprender os tipos de dados mais utilizados na linguagem
    * Você sabia que é possivel aprender 80% de um lingua nova, com cerca de 20% do vocabulário? (até menos)

-------------------------------------------------------------------------------------------------------

# String

- O tipo de dados String consiste em uma cadeia de caracteres, ou seja, textos. Para denotar string no JavaScript são usados aspas duplas ( " " ), aspas simples ( ' ' ) e template literals ou template strings ( ), template literals permitem textos multilinhas e expressões de linguagem com os caracteres ${ }, por exemplo: console.log(A soma de duas unidades é ${1+1}), já as outras não, por exemplo: console.log("Isso é um texto").

* Cadeia de caracteres
    * "" - Aspas duplas
    * '' - Aspas simples
    * `` - Template literals ou templates strings

```js
    console.log("Camilo")
    console.log('Camilo')
    console.log(`Camilo ${1 + 1}`)
```

-------------------------------------------------------------------------------------------------------

# Number

- No JavaScript temos 4 tipos de números, os inteiros (por exemplo: 13), os reais ou float (por exemplo: 83.1), o Not a Number (NaN) e o infinito (Infinity).

* 33 - Inteiros
* 12.5 - Reais - floot
* NaN - Not a Number
* Infinity - Infinito

```js
    console.log(33)
    console.log(12.5)
    console.log(12.5 + 12)
    console.log(12.5 / "asdf")
    console.log(12.5 === Infinity)
    console.log(Infinity)
    console.log(infinity)
```

-------------------------------------------------------------------------------------------------------

# Boolean

- No JavaScript, um dado boolean pode ter apenas 2 valores, verdadeiro (true) e falso (false).

* true - Verdadeiro
* false - Falso

```js
    console.log(true)
    console.log(false)
    console.log(12.5 === Infinity)
```

-------------------------------------------------------------------------------------------------------

# Undefined vs null

- No JavaScript temos o tipo de dados Undefined, que representa valores indefinidos, e o tipo de dados null, que são muitas vezes confundidos. A diferença dos dois é que null é considerado como um objeto vazio, ou seja, algo indefinido não existe, já algo null existe mas não tem valor algum.

* undefined
    * Indefinido

* null
    * Nulo
    * Objeto que não possui nada dentro
    * Diferente de indefinido

```js
    console.log(undefined)
    console.log(null)
```

-------------------------------------------------------------------------------------------------------

# Object

- O tipo de dado Object é estrutural, contendo atributos, ou propriedades, e métodos, ou funcionalidades. Um objeto é denotado com os caracteres { }, atributos e métodos com nome: valor . Por exemplo { nome: "João", idade: 20 }.

* Objeto 
* Propriedades / Atributos
* Funcionalidades / Métodos

{ propriedade: "valor" }

```js
    console.log({
        name: "Camilo",
        idade: 24,
        andar: function(){
            console.log('andar')
        }
    })
```

-------------------------------------------------------------------------------------------------------

# Array (Vetores)

- O tipo de dados Array, ou vetor, também é estrutural, e consiste em uma lista de dados agrupados, um Array é denotado com os caracteres [ ] , por exemplo: [ "Leite", "Ovos", "Manteiga", 1, 2 ] .

* Uma lista 
* Agrupamento de dado

["Camilo", 24]

```js
    console.log([
        "Camilo",
         24,
    ])
    console.log([
        "Leite",
         "Ovos",
         2,
         3
    ])
```

-------------------------------------------------------------------------------------------------------
# Conclusão

- Conforme o ECMAScript Standard (o padrão do orgão que padroniza o JavaScript) temos 9 tipos de dados organizados em 4 categorias: Primitive, Primitive Value, Structural e Structural Primitive. Os primitivos são: String, Number, Boolean, Undefined, Symbol, BigInt. Os estruturais são: Object e Function. Além destes, temos o primitivo estrutural que consiste apenas no dado null

# Tipos de dados

Conforme o ECMAScript standerd temos 9 tipos de dados:

* Data Types
    * Primitive / Primitive value
    * Structural
    * Structural Primitive

## Primitivos

* String
* Number
* Boolean
* undefined
* Symbol
* BigInt

## Estruturais

* Object
    * Array
    * Map
    * Set
    * Date
    * ...
* Function

## Primitivo Estrutural / Structural Root Primitive

* null