# O que é CSS

É responsável pela estilização visual da página HTML. Com CSS podemos colocar estilos nos diversos elementos que compõem uma página com a estrutura HTML.

## Comentando CSS

Para comentar uma ou mais linhas de código CSS.

```css
/* color: green; */
```

## Inserindo CSS no HTML

Existem as formas a seguir que podemos usar para inserir CSS nas páginas.

### Inline

O código CSS fica dentro do elemento HTML

```css
 <p style="color: red;">Texto</p>
```

### Interno

O código fica dentro da tag **\<style>\</style>** na tag **\<head>\</head>** da estrutura HTML.

```css
<head>
  <style>
    h1 {
      color: blue;
      font-size: 12px;
    }
  </style>
</head>
```

### Externo

Usando um arquivo externo que declaramos com a tag **\<link>** na tag **\<head>\</head>**.

```css
<head>
  <link href="arquivo.css" rel="stylesheet"
</head>
```
