# Curso de CSS SASS da Alura

## Variáveis no SASS
### $<Nome_Variavel>: <Propriedade_Variavel>;

## Modularaização no SASS (partials)
### Cria uma pasta Abstract dentro da Pasta Styles. Dentro da pasta Abstract, cria o arquivo _variaveis.scss
### Dentro do arquivo styles.scss inserir - @use './abstract/variaveis'
### Criar uma pasta de Components dentro da Pasta Styles para particionar o css

## Mixins
### Dentro da pasta Abstract, criar um arquivo _mixins.scss
### Exemplo de uma mixin
``` 
@mixin margem-central($width) {
    margin: 0 auto;
    width: $width;
} 
```
### Dentro do componente _header fazer o importe com o @use
### Dentro da tag onde quer colocar o estilo - @include mixins.margem-central(80%);
