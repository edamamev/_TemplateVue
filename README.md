# Vue Template
This template contains Vite + Vue 3 + Tailwind.

## Setup
Get the repo
```zsh
git clone https://github.com/edamamev/_TemplateVue`
```

Install packages
```sh
npm install
```

Ensure your new `tailwind.config.js` has this in it's `content:[]`:
```js
"./src/**/*.{vue,js,ts,jsx,tsx,mdx}",
```

Compile and Hot-Reload for Development
```sh
npm run dev
```

Compile and Minify for Production

```sh
npm run build
```

Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
