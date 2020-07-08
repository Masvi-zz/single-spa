# Single SPA


Estudo de Single SPA, uma ferramenta para integrar framework javascript em um mesmo projeto utilizando conceitos de microservices - Micro frontend.
O projeto roda vue e react. 

# Ferramenta utilizada: [Single SPA](https://single-spa.js.org/docs/getting-started-overview)
O ponto de entrada da aplicação fica definido no webpack.config.js apontando para o single-spa.config.js.

**Referência:** para o desenvolvimento da estrutura inicial utilizei o seguinte tutorial escrito pelo [Nader Dabit
](https://dev.to/dabit3/building-micro-frontends-with-react-vue-and-single-spa-52op)

###### Running 
```
npm start 
```

###### render both apps
http://localhost:8080/

###### render only react
http://localhost:8080/react

###### render only vue
http://localhost:8080/vue
