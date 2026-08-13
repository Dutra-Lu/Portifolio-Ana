# Portfólio — Ana Luiza Dutra

## Arquivos
- `index.html` — página principal do portfólio.
- `style.css` — todo o visual do portfólio.

## Como conectar com a sua Wiki do Brandon Sanderson

O portfólio já possui links para:

```html
<a href="wiki-brandon.html">Minha Wiki</a>
```

e:

```html
<a href="wiki-brandon.html">Conheça minha Wiki</a>
```

### Se a sua página da Wiki estiver na mesma pasta
Por exemplo:

```text
meu-site/
├── index.html
├── style.css
└── wiki-brandon.html
```

não precisa mudar nada.

### Se o arquivo da Wiki tiver outro nome
Se a sua página se chamar `wiki.html`, por exemplo, troque:

```html
href="wiki-brandon.html"
```

por:

```html
href="wiki.html"
```

### Se a Wiki estiver dentro de uma pasta

```text
meu-site/
├── index.html
├── style.css
└── wiki/
    └── index.html
```

use:

```html
href="wiki/index.html"
```

### Se a Wiki estiver publicada em outro site
Use o endereço completo:

```html
<a href="https://seu-link-da-wiki.com" target="_blank" rel="noopener">
    Minha Wiki
</a>
```

## Observação
O conteúdo do portfólio foi baseado nas informações do currículo enviado: Ciência da Computação, Java, Python, HTML, CSS, JavaScript, Node.js, Git/GitHub, IA com Python, desenvolvimento web, experiência em QA/Tester e projeto UNESC Labs/LaModa.
