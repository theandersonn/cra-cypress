```bash
# Caso esteja utilizando Ubuntu/Debian instale as dependencias abaixo
sudo apt-get install libgtk2.0-0 libgtk-3-0 libgbm-dev libnotify-dev libgconf-2-4 libnss3 libxss1 libasound2 libxtst6 xauth xvfb

# Instalar o Cypress
yarn add cypress --dev

# Adicionar script no package.json
"cy:open": "cypress open"

# Instalar plugin cypress eslint
yarn add eslint-plugin-cypress --dev

# Instala o plugin testing-library/cypress
yarn add @testing-library/cypress --dev

# Auxiliar para server (evitar conflitos e efeitos colaterais)
yarn add start-server-and-test --dev
```

### Referências
```bash
# Ferramenta 
https://www.cypress.io/

# Instalacao 
https://docs.cypress.io/guides/getting-started/installing-cypress#Direct-download

# Fix erro `ESLint: 'cy' is not defined (Cypress)`
https://stackoverflow.com/questions/58982852/eslint-cy-is-not-defined-cypress
```
