# Next Level Week 3 - Happy - Web

Projeto do site Happy, realizado no evento Next Level Week 3, trilha Omnistack.

## Tecnologias

* [React](https://pt-br.reactjs.org/)
* [Typescript](http://typescriptlang.org/)

## Instalando dependências

Após clonar o projeto, você pode instalar as dependências usando o gerenciador de pacotes [yarn](https://yarnpkg.com/) com o comando:

```bash
yarn install
```

## Mapas

O app utiliza uma Tilelayer de mapa fornecido pelo [Mapbox](https://www.mapbox.com/). Você pode se cadastrar gratuitamente no site para obter um token de acesso a API. Depois, é necessário que você crie um arquivo .env na raíz do projeto e adicione a seguinte variável de ambiente dentro dele contendo seu token de acesso a API do Mapbox:

```
REACT_APP_MAPBOX_TOKEN=<Seu token de acesso a api>
```

## Rodando seu projeto com `yarn start`

Para rodar o projeto basta utilizar o comando yarn start.