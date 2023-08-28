# app

## setup

```sh
# instala nvm
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash 
# adiciona variaveis globais
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
```

```sh
nvm install node 

# resposta ao erro npm WARN deprecated tar@2.2.2: This version of tar is no longer supported, and will not receive security updates. Please upgrade asap (https://stackoverflow.com/q/68857411)
npm install tar@latest -g

npx create-react-app react-amplified
npm install -g @aws-amplify/cli
```

## referencias

- [https://commit-creator.netlify.app/](https://commit-creator.netlify.app/)
- [https://commitlint.io/](https://commitlint.io/)