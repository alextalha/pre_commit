
# precisamos ter o repositorio git inicializado antes de instalar o husky


yarn add husky -D
npx husky-init && yarn 
yarn global add eslint

npm run prepare

  npx husky add .husky/pre-commit "yarn lint:fix"

