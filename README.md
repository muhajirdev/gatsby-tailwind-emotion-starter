# Gatsby Tailwind Emotion Starter

## Getting Started

Install Gatsby CLI:
```sh
npm install --global gatsby-cli
```

Create new Gatsby project using this starter:
```sh
gatsby new my-new-website https://github.com/muhajirframe/gatsby-tailwind-emotion-starter
```

```sh
cd my-new-website
```

## Usage

### Develop

```
npm run develop
```

### Build

```
npm run build
```
Your built file will be in `/public`

This project was based on [gatsby-plugin-tailwindcss](https://github.com/muhajirframe/gatsby-plugin-tailwindcss/)

### How the heck do I use it?

```javascript
import React from 'react'
import styled from 'react-emotion'


const Container = styled.div`
  ${tw`py-8`};
`
const Text = styled.p`
  ${tw`bg-black text-white`};
`

const Home = () => (
  <Container>
    <Text>I am Text component made with Tailwind CSS + EmotionJS</Text>
  </Container>
)

export default Home
```

### Why would I use it?

Because Tailwind CSS is awesome. If you used [Tachyons](https://tachyons.io/) before. You know how awesome it utility first CSS. Compared to CSS framework like [Bootstrap](http://getbootstrap.com/). -- If you haven't try utility first CSS, give it a try. It's one of the best things in my life --. Tailwind is a more customizable version of Tachyons.

But, because [Tailwind CSS](https://tailwindcss.com) gives you alot of class as utilities. The file size gets bloated. In fact it's 1.5 times bigger than Bootstrap. (https://tailwindcss.com/docs/controlling-file-size )

CSS-in-JS to save.

Fortunately, you can use CSS-in-JS like [Emotion](https://github.com/emotion-js/emotion), to only load needed styles. So you can keep you css size small.

Furthremore, CSS-in-JS is just awesome. [CSS in JS: Benefits, Drawbacks, and Tooling](https://objectpartners.com/2017/11/03/css-in-js-benefits-drawbacks-and-tooling/)

Why Gatsby?
Because Gatsby is blazing fast, and comes with alot of plugins

## For more information

- [Github](https://github.com/muhajirframe/gatsby-tailwind-emotion-starter)
- [gatsby-tailwind-emotion-starter](https://github.com/muhajirframe/gatsby-tailwind-emotion-starter)
- Got a question? [Submit an issue](https://github.com/muhajirframe/gatsby-tailwind-emotion-starter/issues/new)

## Contributing

- [Submit an idea](https://github.com/muhajirframe/gatsby-tailwind-emotion-starter/issues/new)
- Make a pull request

## Related
- [react-tailwind-emotion-starter](https://github.com/muhajirframe/react-tailwind-emotion-starter) A React + Tailwind + EmotionJs starter based on [create-react-app](https://github.com/facebook/create-react-app)
- [vscode-tailwind-styled-snippets](https://github.com/muhajirframe/vscode-tailwind-styled-snippets)
- [gatsby-plugin-tailwindcss](https://github.com/muhajirframe/gatsby-plugin-tailwincss)

**Enjoy!**
