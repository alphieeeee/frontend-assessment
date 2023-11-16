# filta

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## See [GSAP](https://gsap.com/docs/v3/Installation/) for Installation
To Install GSAP Plugin Make sure the "gsap-bonus.tgz" file is in the root directory of the project and run the following command in the terminal. About [GreenSock](https://gsap.com/docs/v3/) plugin.

```sh
npm install ./gsap-bonus.tgz
```

###### Bonus points
* Explain why the result of `('b' + 'a' + + 'a' + 'a').toLowerCase()` is `banana`.
* Because the expression + 'a' is attempting to use the unary plus operator on a string 'a'. The unary plus operator tries to convert its operand to a number. Since 'a' is not a valid number, this conversion results in NaN (Not-a-Number). Then the rest of the expression concatenates the strings 'b', 'a', NaN, and 'a' together. Finally, the toLowerCase() method converts the resulting string to all lowercase letters.