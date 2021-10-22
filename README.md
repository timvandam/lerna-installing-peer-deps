
```zsh
git clone git@github.com:timvandam/lerna-installing-peer-deps.git
cd lerna-installing-peer-deps
npm i
lerna bootstrap
ls packages/my-package/node_modules/@deepkit # core, type (<- this should not be here)
```
