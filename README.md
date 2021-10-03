# Projeto Pré-Commit e Semantic Version

Projeto que estou elaborando para facilitar o processo de padronização de commits e facilitar o release com o semantic version

## Instalação 

```bash
yarn install
```

## Husky

```bash
yarn add husky -D
npm run prepare
npx husky-init && yarn 
yarn global add eslint
```

## Configurando o Pré Commit 

```bash
npx husky add .husky/pre-commit "npx lint-staged"
```

## Configurando o Pré Receive 
Em Breve

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)