
## INSTALAR AS DEPENDÊNCIAS DO PROJETO
yarn install

# PREPARANDO O HUSKY 

yarn add husky -D
npm run prepare
npx husky-init && yarn 
yarn global add eslint

## GERAR OS SCRIPTS DE PRE-COMMIT E PRE-RECEIVE

npx husky add .husky/pre-commit "npx lint-staged"









