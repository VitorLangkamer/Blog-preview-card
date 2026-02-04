# Frontend Mentor - Blog Preview Card

![Blog Preview Card Preview](preview.jpg)

## 🌟 Visão Geral

Este é meu projeto do desafio **Blog Preview Card** do [Frontend Mentor](https://www.frontendmentor.io). Esse desafio foi sensacional para treinar estados interativos. O design parece simples, mas fazer a interação do card ficar fluida e idêntica ao design exigiu atenção aos detalhes!

### 🔗 Links

- Solução URL: [Adicione sua URL aqui]
- Live Site URL: [Adicione sua URL aqui]

## 🛠️ Tecnologias Utilizadas

- HTML5 semântico
- CSS3 customizado
- Flexbox para layout
- Propriedades de `transform` e `transition`
- Manipulação de `box-shadow`
- Google Fonts (Figtree)

## 💡 O Que Eu Aprendi

### 🚀 O Poder do Transform & Transition

O grande aprendizado desse projeto foi dominar a interatividade. Eu queria que o card parecesse "clicável" e vivo. Aprendi a combinar `transition` (para suavizar) com `transform` (para mover):

- **Transition**: Define o tempo e a curva de velocidade da animação.
- **Transform**: Move o elemento nos eixos X e Y sem afetar o layout ao redor.

```css
/* O segredo do movimento suave */
.card {
    transition: all 0.3s ease-in-out;
    box-shadow: 8px 8px 0px #000; /* Sombra sólida inicial */
}

.card:hover {
    cursor: pointer;
    box-shadow: 16px 16px 0px #000; /* Sombra cresce */
    transform: translate(-4px, -4px); /* Card sobe e vai pra esquerda */
} 
```

## 🎨 Sombras Sólidas (Hard Shadows)
Diferente das sombras suaves que costumava usar, aqui aprendi a fazer sombras sólidas para dar esse visual mais "pop" e moderno. O segredo é não usar o "blur" (terceiro valor do box-shadow):

box-shadow: [eixo-x] [eixo-y] [blur-radius] [cor]; -> box-shadow: 8px 8px 0px #000; (O 0px no blur faz a sombra ficar dura).

## 🧩 Estrutura HTML Semântica
Reforcei o uso de tags semânticas para o blog:

<article> para o card em si.

<time> para a data de publicação.

<figure> para a imagem de destaque.

## 🚀 Desenvolvimento Contínuo
Áreas que quero melhorar nos próximos:

[ ] Explorar CSS Grid para layouts mais complexos

[ ] Melhorar a acessibilidade com foco no teclado (:focus-visible)

[ ] Otimizar imagens para performance

## 👨‍💻 Autor
Frontend Mentor - @VitorLangkamer

GitHub - @VitorLangkamer