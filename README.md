# CSS Avançado

# Arquitetura CSS: Descomplicando os problemas (Curso 0/4)

![screenshot](https://github.com/divertimentos/advanced-css/blob/main/media/0-arquitetura-screenshot.jpg)

## Coisas novas que aprendi

### BEM (Block, Element, Modifier)

- `bloco`
- `bloco__elemento`
- `bloco--modificador`
- `bloco__elemento--modificador`

### Calc

- Para que um banner se estendesse por toda a tela (`height: 100vh;`), mas desconsiderasse a altura da navbar, aprendi a usar a função `calc();` para subtrair 72 pixels:

```css
.banner__imagem {
  height: calc(100vh - 72px);
  width: 100%;
}
```

## Media queries (Responsividade)

```css
@media screen and (min-width: 768px) {
  .selector {
    padding: 2.5rem;
  }
} ;
```

# Flexbox: Posicione elementos na tela (Curso 1/4)

![flexbox-screenshot](https://github.com/divertimentos/advanced-css/blob/main/media/1-flexbox-screenshot.png)

# CSS Grid: Simplificando Layouts (Curso 2/4)

## Coisas interessantes que aprendi:

### Shorthands

- Podemos usar um _shorthand_ para o `background()`. Em vez de:

```css
background-image: url("../img/fortnite.jpg");
background-position: center;
background-repeat: no-repeat;
background-size: cover;
```

pode-se utilizar apenas:

```css
background: url("../img/fortnite.jpg") center / cover no-repeat;
```

- Há também um shorthand para `grid-column` e `grid-row`. Em vez de:

```css
grid-column-start: 1;
grid-column-end: 4;

grid-row-start: 1;
grid-row-end: 3;
```

podemos utilizar:

```css
grid-column: 1 / 4;
grid-row: 1 / 3;
```

Na última aula, na seção sobre responsividade nos cards (Seção chamada "Populares"), aprendi alguns detalhes sobre responsividade, como não repetir um seletor se ele se estender ao próximo media query.

Não aprendi muita coisa com esse curso. Foi basicamente um demonstrativo da sintaxe do Grid Layout, mas de forma confusa e "jogada". Posteriormente vou precisar revisitar o assunto a partir de outras fontes, outros cursos, artigos etc., para assimilar melhor as informações contidas neste curso. Para uma introdução ao assunto, o curso beira o satisfatório; porém, para apreender de fato todas as informações contidas aqui contextualmente de forma a sair usando o Grid, seria necessário repetir o curso mais algumas vezes. _Not today, though_.

Uma outra coisa impossível de deixar de notar é o áudio do curso. Você fica ouvindo constantemente o som do professor engolindo saliva e fazendo pequenos barulhos com a boca. É nojento. A Alura tem controle de qualidade 0 sobre a forma como seus cursos são feitos.

# Sass: O CSS com superpoderes (Curso 3/4)

# Layouts Responsivos: Trabalhando com layouts mobile (Curso 4/4)
