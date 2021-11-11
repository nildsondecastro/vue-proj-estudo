# vue-fire-estudo

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Comandos utilizados apos a criação

- `npm install --save bootstrap`

- `npm install --save @fortawesome/fontawesome-free`

## 1

- app.scss criado, nele foram importados o bootstrap e o fontawesome
- A fonte foi modificada e percebeu-se a mudança
- No main.js foi importado o app.scss

1-1
- Deletei conteúdo do App.vue
- Deletei componente HelloWorld (deu erro, para resolver tive que apagar a linha do home.vue de import do helloworld)

## 2

- Adicionei o primeiro componente e importei ele
- Percebi erros se identação e estilo do codigo, provavelmente devido a configuração do eslint
- Adicionei dados ao componente

- Criei um novo componente e importe ele, mas agora com outra forma de tag: life-cycle
- tive erros por ter ; 
    por ter espaço a mais
     e por ter linha a mais
- setTimeout
