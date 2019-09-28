# cowsay-truffle

```bash
# entrar no home no diretorio .ethereum
cd ~/.ethereum

# clonar o repositorio: Ethereum Finchain Course
git clone https://github.com/glauberdm/EthereumFinchainCourseToken.git

# entrando no diretorio
cd EthereumFinchainCourseToken

# instalando 
npm i

npm install

> scrypt@6.0.3 preinstall /Users/renato/.ethereum/EthereumFinchainCourseToken/node_modules/scrypt

> node node-scrypt-preinstall.js
> fsevents@1.2.9 install /Users/renato/.ethereum/EthereumFinchainCourseToken/node_modules/fsevents

> node install

node-pre-gyp  WARN  Using request for node-pre-gyp https download

[fsevents] Success: "/Users/renato/.ethereum/EthereumFinchainCourseToken/node_modules/fsevents/lib/binding/Release/node-v72-darwin-x64/fse.node" is installed via remote
> keccak@1.4.0 install /Users/renato/.ethereum/EthereumFinchainCourseToken/node_modules/keccak
> npm run rebuild || echo "Keccak bindings compilation fail. Pure JS implementation will be used."
> keccak@1.4.0 rebuild /Users/renato/.ethereum/EthereumFinchainCourseToken/node_modules/keccak
> node-gyp rebuild
```

```bash
 __________________________________ 
< Aqui começa a chuva de Warning! >
 ---------------------------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

```bash
> core-js@2.6.9 postinstall /Users/renato/.ethereum/EthereumFinchainCourseToken/node_modules/core-js
> node scripts/postinstall || echo "ignore"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting of core-js on Open Collective or Patreon: 
> https://opencollective.com/core-js 
> https://www.patreon.com/zloirock 

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)

npm WARN EthereumFinchainCourse@ No repository field.
npm WARN EthereumFinchainCourse@ No license field.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: scrypt@6.0.3 (node_modules/scrypt):
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: scrypt@6.0.3 install: `node-gyp rebuild`
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: Exit status 1

added 705 packages from 477 contributors and audited 8940 packages in 263.128s
found 1 low severity vulnerability
run `npm audit fix` to fix them, or `npm audit` for details
```
```bash
 _______________________ 
< WARN = Segue o baile! >
 ----------------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

```bash
 # rodando a aplicacao
 npm run dev

> EthereumFinchainCourse@ dev /Users/renato/.ethereum/EthereumFinchainCourseToken
> lite-server

** browser-sync config **
{
  injectChanges: false,
  files: [ './**/*.{html,htm,css,js}' ],
  watchOptions: { ignored: 'node_modules' },
  server: {
    baseDir: [ './src', './build/contracts' ],
    middleware: [ [Function], [Function] ]
  }
}
[Browsersync] Access URLs:
 -------------------------------------
       Local: http://localhost:3000
    External: http://172.16.70.62:3000
 -------------------------------------
          UI: http://localhost:3001
 UI External: http://localhost:3001
 -------------------------------------
[Browsersync] Serving files from: ./src
[Browsersync] Serving files from: ./build/contracts
[Browsersync] Watching files...
19.09.28 09:55:50 200 GET /index.html
19.09.28 09:55:50 200 GET /js/bootstrap.min.js
19.09.28 09:55:50 200 GET /css/bootstrap.min.css
19.09.28 09:55:50 200 GET /js/app.js
19.09.28 09:55:50 200 GET /js/web3.min.js
19.09.28 09:55:50 200 GET /js/truffle-contract.js
19.09.28 09:55:53 200 GET /EthereumFinchainCourse.json
19.09.28 09:55:53 404 GET /favicon.ico
```

```bash
 _________________________________________ 
/ Wow! o chrome vai abrir e você conecta \
\ o MetaMask!                             /
 ----------------------------------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

Agora, vamos dar uma olhada na estrutura de arquivos desse projeto, que é bem similar a um projeto web. Utilizando um Editor (ex.: VisualCode), vamos dar uma olhada no código.

```bash
# se tiver instalado o VisualCode digite:
code .
```

