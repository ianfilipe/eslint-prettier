# eslint-prettier

Repositório para consulta sobre como instalar o ESLint e o eslint-config-prettier para projetos React com TypeScript.

## ESLint

Para instalar e configurar o ESLINT, rode o comando:

### `npm init @eslint/config`

Documentação: [Getting Started with ESLint
](https://eslint.org/docs/latest/user-guide/getting-started)

## eslint-config-prettier

Para instalar o eslint-config-prettier, rode o comando:

### `npm install --save-dev eslint-config-prettier prettier`

Depois adicione `"prettier"` no "extends" do arquivo `.eslintrc`. Coloque ele por último para sobrescrever outras configurações.

Documentação: [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)

## Suprimir erros por falta do 'import React'

Adicione `"react/react-in-jsx-scope": "off"` no "rules" do arquivo `.eslintrc`.
