# Anotações | Aula 1 Sass

## para instalar:
```
npm install -g node-sass
```
ou para abreviar: 
```
npm i -g node-sass
```

## compilando um arquivo sass:
node-sass style.scss style.css

``--watch`` serve para deixar a compilação rodando

node-sass --wacth style.scss style.css


## Pseudo classe

A pseudo classe é feita atráves do `&` que seleciona o elemento pai
``` css
a {
    color: #ffa;
    &:hover {
        color: #faf;
    }
}
```

## Maps

### Lembrente
Fazer os exercícios da aula que estarão no portal do aluno
