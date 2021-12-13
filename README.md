# Vue3: Começando com o framework

## Módulo 1

- Iniciar um projeto novo, utilizando TypeScript e Vue3;
  - Aprendemos como instalar e utilizar o vue cli para construir um novo projeto, customizando inclusive as dependências que teremos.

- Importar o Bulma;
  - Fazendo uma única importação, no index.html, passamos a ter disponível todos as facilidades desse framework CSS.

- Criar componentes;
  - Para cada novo componente, criamos um arquivo Vue com as seguintes sessões: `template` para o html, `script` para o comportamento e `style` para o visual.

- Escutar eventos de clique;
  - O Vue nos ajuda a trabalhar com eventos, basta utilizarmos a sintaxe `@nomeDoEvento` direto no elemento que queremos ouvir.

- Trabalhar com intervalos.
  - O `setInterval` é perfeito para nosso cenário, de incrementar o tempo decorrido a cada segundo.

## Módulo 2

- Refatorar componentes em componentes menores;
  - Vimos que é muito fácil atribuir funcionalidades demais a um componente existente. Quando isso aconteceu, aprendemos a refatorar o componente em componentes menores e mais coesos.

- Formatar a exibição de X segundos em HH:mm:ss;
  - Aprendemos que podemos construir um objeto `Date` passando em seu construtor a quantidade de microsegundos decorridos. Depois, fatiamos a string para pegarmos somente as horas, minutos e segundos.

- Emitir eventos customizados;
  - Aprendemos a utilizar o [`$emit`](https://v3.vuejs.org/guide/component-custom-events.html) para criar eventos utilizados na comunicação entre componentes.

- Ouvir eventos customizados.
  - Aprendemos que ouvir eventos customizados é tão simples quanto ouvir eventos HTML, como o `click` por exemplo.


## Módulo 3

- Renderizar listas com o `v-for`;
  - Utilizamos um mecanismo de repetição para renderizar N vezes uma tarefa, onde N é o tamanho da lista. Isso faz com que nossa lista seja dinâmica.
- Condicionais com `v-if` / `v-else`;
  - Aprendemos como esconder ou exibir um componente, dado um estado específico utilizando a diretiva `v-if`.
- Fallback de conteúdo com o operador `||` (OU);
  - Utilizamos o operador OU para exibir um texto padrão, caso a tarefa não possua uma descrição.
- Slots.
  - Aprendemos a lidar com o slot quando criamos um componente para representar o Box. Assim, conseguimos exibir os elementos filhos dentro do nosso Box.

# alura-tracker

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
