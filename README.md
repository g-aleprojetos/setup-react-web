<H1 align="center">SETUP REACTJS WEB</H1>

<div align="center">


[![Coverage Status](https://coveralls.io/repos/github/g-aleprojetos/setup-react-web/badge.svg?branch=main)](https://coveralls.io/github/g-aleprojetos/setup-react-web?branch=main)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![MIT Licensed](https://img.shields.io/badge/license-MIT-green.svg)](https://tldrlegal.com/license/mit-license)


</div>

## Setup

- Ferramentas necessárias:
  - Visual Studio Code
  - Git
  - yarn (1.22.18)
  - React (18.2.0)
  - Typescript
  - Prettier (plugin do VSCode recomendado)
  - ESLint (plugin do VSCode recomendado)

## Políticas de Código

[Políticas e padrões de código](./docs/padroes-de-codigo.md)
</br></br>

## Pagina em produção
### [https://g-aleprojetos.github.io/setup-react-web/](https://g-aleprojetos.github.io/setup-react-web/)

</br></br>
### Clonar projeto

```shell
git clone https://github.com/g-aleprojetos/setup-react-web.git
```
### Instala as bibliotecas

```shell
yarn install
```

## Executar o projeto na máquina local

```shell
yarn start
```

## Executando teste
- Para rodar os testes, executar o comando:
```shell
yarn test
```

- Para atualizar os snapshots, executar o comando:
```shell
yarn test -u
```

- Executar os testes e emite o reatório coverage:
```shell
yarn run test --coverage --watchAll
```