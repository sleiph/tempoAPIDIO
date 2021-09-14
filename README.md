# API de previsão do tempo 🌩

Criando projeto para consultar a previsão do tempo via API externa do [OpenWeather](https://openweathermap.org).

## Comandos

O projeto usa a [Angular CLI](https://github.com/angular/angular-cli).

pra rodar o servidor de desenvolvimento:
```
ng serve
```

fica online na porta [:4200](http://localhost:4200/)

pra gerar um novo componente:
```
ng generate component component-name
```

buildar:
```
ng build
```

testes:
```
ng test
```

## API Key

Eu criei o arquivo não rastreado `env.js` dentro da pasta `environment`, pra guardar a minha chave do OpenWeather.

Então pra usar o app vc precisa:
1. duplicar o arquivo `env-exemplo`,
2. renomear pra env
3. adicionar sua própria chave.

Desculpa qualquer coisa, fiz isso porque o GitHub brigou comigo e eu sou covarde.

## Projeto original

[João Ghignatti](https://github.com/JGhignatti/jv-weather), no Bootcamp de Angular e Java da [DIO](https://web.digitalinnovation.one).
