git fetch --all --tags -p
git merge upstream/master


nvm use 12
yarn
yarn run watch

parallel:
./scripts/code.sh

in code dann "reload window" bei änderungen

alternativ zu ./scripts/code.sh: yarn run web
ist das dann mit live reload?
wie kann das eigene sources editieren?


