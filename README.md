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

## 3 Hierarquia de Componentes

- Criei o componente Pessoa.vue, escrevi o template, escrevi o script
- Importei ele no App.Vue

- Criei o Info.vue, escrevi o template, escrevi o script
- Importei ele no Pessoa.vue

- Criei o Form.vue, escrevi o template, escrevi o script
- Criei uma pasta chamada form dentro da pasta de componentes
- Dentro da pasta form criei o InputText.vue
- Dentro da pasta form criei o Submit.vue
- Importe o Submit.vue e o InputText.vue para o Form.vue
- Importei o Form.vue para o Pessoa.vue

## 4

- Dentro de Info, criei a variavel esta_trabalhando e testei por meio do v-if