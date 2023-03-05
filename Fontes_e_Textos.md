# Trabalhando com fontes

Tipografia transmite mensagem

    - negrito
    - tamanho
    - estilo

-------------------------------------------------------------

## Basic Font Properties

* font-family
* font-weight
* font-style
* font-size

-------------------------------------------------------------

## Font Family

* Tipo de fonte de um elemento
* Lista de fontes e ordem de prioridade
* inclui *fallback* font

```css
p {
    font-family: "Times New Roman", Timer, serif;
}

```

    - serif
    - sans

-------------------------------------------------------------

## Font Weight
* Peso da fonte
* Valores: normal | bold | bolder | lighter | 100 | 200 |  300 | 400 | 500 | 600 | 700 | 800 | 900
* Dependendo da família da fonte não conseguimos utilizar todos os pesos de fonte

```css
p {
    font-weight: bold;
}
```

https://www.w3.org/TR/css-fonts-3/

-------------------------------------------------------------

## Font Style

* O Estilo da fonte
* Valores: normal | italic | oblique
* Os valores que podem ser aplicados dependem da fonte usada

```css
span {
    font-style: italic;
}
```

-------------------------------------------------------------

## Font Size

* O tamanho da fonte

```css
p {
    font-size: 18px;
}
```

-------------------------------------------------------------

## Web Fonts

- fontes do sistema x fontes da web
    * Fontes do sistema são as fontes que estão instaladas na máquina do usuário e nem sempre o cliente vai ter instalado as fontes usadas no projeto e isso pode fazer com que os estilos dos textos não sejam aplicados corretamente, mas para resolver esses casos podemos preparar nossas fonts para web ou usar fontes da web.
- como usar fontes para web?

    * @font-face
    * @import
    * link

### Referências

https://www.w3.org/TR/css-fonts-3/
https://css-tricks.com/snippets/css/using-font-face-in-css/
https://fonts.google.com/

-------------------------------------------------------------
# Font-variant e font-stretch

## Font Variant

* Faz variações na apresentação da fonte

```css
p {
	font-variant: small-caps;
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant

## Font Stretch

* Alargamento ou encolhimento da fonte
* Aceita palavras-chaves como: expanded, condensed, normal
* Aceita porcentagens de 50% a 200%
* Essa propriedade não vai funcionar em todas as fontes

```css
p {
	font-stretch: expanded;
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/font-stretch

### Referência

https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals

-------------------------------------------------------------

# Letter e word-spacing

## Letter spacing

* Define o espaçamento entre os caracteres

```css
p {
	letter-spacing: 4px;
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing

## Word spacing

* Define o espaçamento entre palavras

```css
p {
	word-spacing: 1em;
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/word-spacing

-------------------------------------------------------------

# Line-height e text-transform

## Line height

* Define os espaços entre linhas
* Pode ser com unidades ou sem unidades de medida
* Valores comuns: 1.5 ou 2

```css
p {
	line-height: 1.5;
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/line-height

## Text transform

* Transformação do texto
* Valores podem ser: none | capitalize | uppercase | lowercase | full-width | full-size-kana

```css
p {
	text-transform: uppercase;
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform

-------------------------------------------------------------

# Text-decoration

## Text decoration
* Aparência decorativa de um texto
* line: underline | overline | line-through
* podemos aplicar mais de 1 valor
* style: wavy | dotted | double | dashed | solid
* color: <color> values

```css
h1 {
	text-decoration: underline; /* shorthand */
}

p {
  text-decoration: wavy overline blue; /* shorthand */
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration

-------------------------------------------------------------

# Text-align

## Text align
* Alinhamento de um texto
* Valores: start | end | left | right | center | justify | match-parent

```css
p {
	text-align: center;
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/text-align

-------------------------------------------------------------

# Text-shadow

## Text shadow
* Sombra aplicada a um texto
* Permite múltiplos valores

```css
p {
  text-shadow: 1px 1px 1px red,
	       2px 2px 1px green; /* offset-x | offset-y | blur-radius | color */
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow

-------------------------------------------------------------

# Shorthand

* Podemos usar o shorthand font para determinar os seguintes valores: font-style, font-variant, font-weight, font-stretch, font-size, line-height e font-family

```css
p {
  /* -style, -variant, -weight, -stretch, -size, -line-height, e -family. */
  font: italic normal bold normal 3em/1.5 Helvetica, Arial, sans-serif;
}
```