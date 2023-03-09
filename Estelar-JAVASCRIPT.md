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

-------------------------------------------------------------------------------------------------------

# Variaveis

- Para entender variáveis podemos pensar nelas como nomes simbólicos para algum valor, atalhos de código ou identificadores. Para criar uma variável, podemos usar uma das palavras reservadas: var, let e const, por exemplo: var clima = "quente", onde var é a palavra que simboliza a criação da variável, clima é o nome da variável, o sinal de igual denota que a variável está recebendo um valor e "quente" é a string que está sendo recebida. As variáveis declaradas com "var" e "let" podem ter seu valor mudado, já a const não.

* Nomes simbólicos para receber algum valor
* Atalhos de código
* Identificadores
* 3 palavras reservadas para criar uma variável
    * var
    * let
    * const

```js
    <script>

        // var
        var clima = "Quente"
        clima = "Frio"

        console.log(clima)

        // let
        let clima = "Quente"
        clima = "Frio"

        console.log(clima)
        
        // const
        const clima = "Quente"
        clima = "Frio"

        console.log(clima)
        
    </script>
```

-------------------------------------------------------------------------------------------------------

# Tipos dinâmicos

- O JavaScript é uma linguagem fracamente tipada e dinâmica, ou seja, ao declarar uma variável não é necessário estabelecer um tipo específico e o tipo do valor da variável pode mudar conforme o código.
- Variáveis não precisam ter um tipo previamente definido
- Podemos mudar o conteúdo da variável

```js
    <script>

        let clima = ""
        console.log(typeof clima)

        clima = 0
        console.log(typeof clima)

        clima = true
        console.log(typeof clima)

    </script>
```

-------------------------------------------------------------------------------------------------------

# Scope e var

- O Scope ou Escopo determina a visibilidade de uma variável em um código, e para entender scope precisamos primeiramente entender block statement, que é o código presente dentro de chaves. O escopo do var é global, ou seja, uma variável declarada com var poderá ser usada em todo o código.

* Escopo determina a visibilidade de alguma variável no JS

## Block statement

```js
// vamos iniciar um bloco
{
    // aqui dentro é um bloco e posso colocar qualquer código
} // aqui fechamos o bloco
```

```js

{
    let x = 0
    console.log(x)
}
```

O bloco, também criará um novo escopo. Chamamos de `block-scoped`

### var
```js
// var é global e poderá funcionar fora de um escopo de bloco
console.log('> existe x antes do bloco? ', x)
{
    var x = 0
}

console.log('> existe x depois do bloco? ', x)
```

# Scope let e const
- Diferentemente de var, const e let são variáveis com escopo local, ou seja, só são visíveis no escopo onde foram criadas e em escopos interiores ao de criação. Em uma variável let, porém, pode-se alterar o valor em um escopo e o valor irá persistir no escopo de criação.

## let e const
```js
// const e let são locais e só funcionam no escopo onde foi criada
console.log('> existe y antes do bloco? ', y)
{
    let y = 0
}

console.log('> existe y depois do bloco? ', y)
// Não irá funcionar. O jeito correto é:

{
    let y = 0
    console.log('> existe y? ', y)
}

// outra forma
let y = 1
{
    let y = 0
    console.log('> existe y? ', y)
}

console.log('> existe y depois do bloco?', y)
```

# Nomeando variáveis

- Para nomearmos variáveis corretamente e de um jeito inteligente, precisamos saber de algumas coisas, como: JavaScript é case-sensitive (sensível à letras maiúsculas e minúsculas) e aceita a cadeia de caracteres Unicode, podendo receber acentuações. Em um nome de variável em JS você pode: Iniciar com caracteres especiais, iniciar com letras e colocar acentos, lembrando sempre que letras maiúsculas e minúsculas fazem a diferença. Em contraste, você não pode: Iniciar com números e colocar espaços vazios. Idealmente você deve colocar nomes significativos, que fazem sentido na aplicação, explicando o que a variável é, usando camel case, onde a primeira palavra de uma frase é toda minúscula, e as subsequentes não se separam por espaço e tem a primeira letra maiúscula, por exemplo: oNomeDessaVariável, e usar nomes em inglês.

## Para criar nomes

* JS é case-sensitive (sensível ao caso)
* JS aceita a cadeia de caracteres Unicode

- Posso:
    * Iniciar com esse caracteres especiais $ _
    * Iniciar com letras
    * Colocar acentos
    * Letras maíusculas e minúsculas fazem diferença

- Não posso:
    * Iniciar com números 
    * Colocar espaços vazios no nome

- Ideal:
    * Criar nomes que fazem sentido
    * Qyue explique o que a variável é ou faz
    * camelCase
    * snake_case
    * Escrever em inglês

-------------------------------------------------------------------------------------------------------

# Declaration assignment var
- Para declarar uma variável podemos usar var, let e const, e para atribuírmos valores à essa variável utilizamos o caractere =, e para vermos o tipo dessa variável podemos utilizar a função /*console.log(typeof variavel)*/.

```js
    // Variáveis e tipos de dados

    // declaração or declaration
    var name

    // assignment or atribuição de valores
    name = "Camilo"

    // que tipo de dado foi colocado na variável
    console.log(typeof name)
    console.log(name)

```

# Agrupando declarações
- É possível agrupar diversas declarações de variáveis em JavaScript usando let, const ou var e colocando uma vírgula entre os nomes das variáveis a serem criadas, por exemplo: *let name, age, isStudent*. Para mostrar mais de uma variável no console.log também é possível usando vírgula, por exemplo: *console.log(name, age, isStudent)*.

```js
    // Variáveis e tipos de dados

    // declaração or declaration
    var name

    // assignment or atribuição de valores
    name = "Camilo"

    // que tipo de dado foi colocado na variável
    console.log(typeof name)
    console.log(name)

    // agrupamento de declarações
    let age, isHuman
    age = 24
    isHuman = true

    console.log(name, age, isHuman)

```

# Concatenando e interpolando variáveis
- É possível concatenar strings com o operador +, por exemplo: *console.log('o ' + name + ' tem ' + age + ' anos.')* desta maneira as variáveis serão convertidas em texto e o que será mostrado será um texto com o nome e a idade que foram estabelecidas no código. Uma outra maneira de escrever um texto com variáveis é por meio da interpolação com template literals, usando crase para o texto e ${} para denotar uma variável, por exemplo *console.log(`O ${name} tem ${age} anos.`)* o resultado deste comando será o mesmo texto do anterior.

```js
    // Variáveis e tipos de dados

    // declaração or declaration
    var name

    // assignment or atribuição de valores
    name = "Camilo"

    // que tipo de dado foi colocado na variável
    console.log(typeof name)
    console.log(name)

    // agrupamento de declarações
    let age, isHuman
    age = 24
    isHuman = true

    // multiplos argumentos na funcao
    //console.log(name, age, isHuman)

    // escrita de texto + variáveis

    // concatenando valores
    console.log('o ' + name+ ' tem' + age + ' anos.')

    // interpolando valores com template literals or template strings
    console.log(`o ${name} tem ${age} anos`)

```

# Objects
- Para criarmos um objeto utilizamos as chaves envolvendo as propriedades, que são atribuídas com dois pontos, por exemplo: *const person = { name: 'John', age: 20 }*, para acessar essas propriedades usamos o ".", por exemplo: console.log(person.name).

```js
    // Object
    const person = {
        name: 'John',
        age: 30,
        weight: 105,
        isAdmin: true
    }

    console.log(`${person.name} tem ${person.age} anos`)
```

# Arrays
- Para criarmos um vetor utilizamos [ ] envolvendo os valores, por exemplo: *const animals = [ "Lion", "Monkey" ]*, para acessar esses valores usamos a posição do valor no vetor, começando por 0, por exemplo: *console.log(animals[0])*. Para descobrirmos o número de posições de um vetor qualquer, podemos utilizar a propriedade length, por exemplo: *animals.length*.

```js
const animals = [
    'Lion',
    'Monkey',
    {
        name: 'Cat',
        age: 3
    }
]

// acessar valores dentro do Array
console.log(animals[0])
console.log(animals.length)
console.log(animals[2].name)
console.log(animals[1].name)
```

-------------------------------------------------------------------------------------------------------

# Functions
- Funções são tipos de dados estruturais, que são declarados dessa forma: *function nomeFunção() { código à cer executado }* e para executar a função, usa-se: *nomeFunção()*. Uma função é importante para o agrupamento e reutilização de código.

```js
// criar um aplicativo de frases motivacionais


// declaration - declaração da função
// function statement
function createPhrases () {
    console.log('Estudar é muito bom')
    console.log('Paciência e persistência')
    console.log('Revisão é mãe do aprendizado')
}

// executar a função
// rodar, chamar, invocar
// execute, run, call, invoke
createPhrases()
createPhrases()
createPhrases()

console.log('fim do programa')
```

## Argumentos e parâmetros
- Também é possível declarar funções dentro de variáveis, desta maneira: *const variavel = function() {}*. Uma parte importante de funções são os parâmetros, que são similares variáveis que funcionam para colocar dados em funções, eles são declarados junto à declaração da função e quando a função for executada, os valores dos argumentos são colocados dentro dos parênteses.