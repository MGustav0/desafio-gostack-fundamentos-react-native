# GoMarketplace

## Desafio 08: Fundamentos do React Native

![Badge](https://img.shields.io/badge/Bootcamp%20Rocketseat-React%20Native-blueviolet) ![Badge](https://img.shields.io/badge/types-Flow%20%7C%20TypeScript-blue)

> Status do Projeto: :heavy_check_mark: Concluído

## Descrição do projeto

[Nesse desafio](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-fundamentos-react-native), desenvolverei uma aplicação de gestão de marketplace, a GoMarketplace, em sua parte front-end mobile. O foco será em Android.

## Linguagens, dependencias e libs utilizadas :books:

- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

## Funcionalidades

:heavy_check_mark: Listar produtos da API.

:heavy_check_mark: Adicionar e exibir itens ao carrinho de compras.

:heavy_check_mark: Diminuir e aumentar a quantidade de itens do carrinho de compras.

:heavy_check_mark: Exibir valor total dos itens do carrinho de compras.

## Iniciando banco de dados

Antes de tudo, para que você tenha os dados para exibir em tela, foi criado um arquivo que você poderá utilizar como __fake API__ para te prover esses dados.

Para isso, foi instalado no package.json uma dependência chamada json-server, e um arquivo chamado server.json que contém os dados para uma rota __/products__. Para executar esse servidor você pode executar o seguinte comando:

```bash
yarn json-server server.json -p 3333
```

## Como rodar a aplicação :arrow_forward:

1. No terminal, clone o projeto: `git@github.com:MGustav0/desafio-gostack-fundamentos-react-native.git`

2. Acesse a pasta via terminal.

3. Instale as dependencias: `yarn`

4. Execute: `yarn start`

5. Em outro terminal: `yarn android`

## Como rodar os testes

```bash
yarn test
```

## Layout da Aplicação :dash:

### Dashboard

<img src="https://github.com/MGustav0/desafio-gostack-fundamentos-react-native/blob/master/extras/01_-_dashboard.jpg" width="270" heigth="480" />

### Carrinho de Compras

<img src="https://github.com/MGustav0/desafio-gostack-fundamentos-react-native/blob/master/extras/02_-_cart.jpg" max-width="270" max-heigth="480" />

## Resolvendo Problemas :exclamation:

Me conte [aqui](https://github.com/MGustav0/desafio-gostack-fundamentos-react-native/issues).

## Licença

[Template](https://github.com/Rocketseat/gostack-template-fundamentos-react-native) escrito pela Rocketseat para o Bootcamp.

[Interface](https://www.figma.com/file/VgK3hsmyGbqiGu9FdqfUzF/GoMarketplace?node-id=0%3A1) desenhada pela Rocketseat para o Bootcamp.

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
