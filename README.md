

# cowsay-truffle: Truffle Suite Foundation hands on

```bash
FIAP - Truffle Suite Foundation

< Aula: Truffle Suite Foundation -
< Prof. GLAUBER DUARTE MONTEIRO >
 -----------------------------
     \   ^__^
      \  (oo)\_______
         (__)\       )\/\
            ||----w |
            ||     ||
by Renato Puga
```

# Sobre cowsay-truffle

Acabei desistindo da Virtual Machine (VM) e instalei os softwares e dependências anteriores no OSX 10.14 Majove.

# Aula 01

Reativando a VM e instalando o Projeto EthereumFinchainCourseToken.

# P1: Ethereum Finchain Course Token

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
# se estiver instalado o VisualCode digite:
code .
```

# P2: Ethereum Finchain Course API

```bash
# volte para o home no dir .etherum
cd ~/.ethreum

# clonando o projeto
git clone https://github.com/glauberdm/EthereumFinchainCourseAPI.git
Cloning into 'EthereumFinchainCourseAPI'...
remote: Enumerating objects: 83, done.
remote: Counting objects: 100% (83/83), done.
remote: Compressing objects: 100% (51/51), done.
remote: Total 83 (delta 18), reused 83 (delta 18), pack-reused 0
Unpacking objects: 100% (83/83), done.

# entrando no diretorio clonado
cd EthereumFinchainCourseAPI/

# instalando (chuva de WARN e ERR)
npm install

```

```bash
 ______________________________________ 
/ Chuva de WARN e ERR, o Glauber disse \
\ que no IOS é pior! Obrigado!         /
 -------------------------------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

```bash

# .... rodei de novo e apareceu isso!
npm install

npm WARN ethereum-finchain-course-api@ No repository field.
npm WARN ethereum-finchain-course-api@ No license field.

audited 4128 packages in 3.548s
found 540 vulnerabilities (204 low, 18 moderate, 316 high, 2 critical)
  run `npm audit fix` to fix them, or `npm audit` for details

# fui bem conservador e executei o que foi recomendado
npm audit fix 

# e depois...
npm audit fix --force

# vamos rodar (crendeuspai)
npm run start

> ethereum-finchain-course-api@ start /Users/renato/.ethereum/EthereumFinchainCourseAPI
> node app.js

Application started. http://localhost:10010/api/v1/doc

```

```bash
 _____________ 
< WoW! Rodou! >
 ------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```


# P3: Ethereum Finchain Course Vote

```bash
# voltando para o home ethereum
cd ~/.ethereum

# clonando repositorio EthereumFinchainCourseVote
git clone https://github.com/glauberdm/EthereumFinchainCourseVote.git
Cloning into 'EthereumFinchainCourseVote'...
remote: Enumerating objects: 85, done.
remote: Counting objects: 100% (85/85), done.
remote: Compressing objects: 100% (50/50), done.
remote: Total 85 (delta 31), reused 85 (delta 31), pack-reused 0
Unpacking objects: 100% (85/85), done.

# entrando no repositorio
cd EthereumFinchainCourseVote/

# instalando com npm
npm install 
```

```bash
 ______________________ 
< WARN = Segue o Baile >
 ---------------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

```bash

# rodando o projeto
npm  run dev

> ethereum-finchain-course-vote@ dev /Users/renato/.ethereum/EthereumFinchainCourseVote
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
19.09.28 14:07:17 200 GET /index.html
19.09.28 14:07:17 200 GET /js/bootstrap.min.js
19.09.28 14:07:17 200 GET /css/bootstrap.min.css
19.09.28 14:07:17 200 GET /js/app.js
19.09.28 14:07:17 200 GET /js/web3.min.js
19.09.28 14:07:17 200 GET /js/truffle-contract.js
19.09.28 14:07:18 200 GET /ColorDecision.json
````

Agora, abra com o VisualCode o diretório do projeto e edite o arquivo `truffe-config.js` as seguintes linhas:

```bash
//  compilers: {
//    solc: {
//      // version: "/Users/glauber/.nvm/versions/node/v12.10.0/lib/node_modules/solc",   // Any published image name
//      version: "0.4.20",
//      docker: true
//    }
//  }
```

Salve a alteração e agora no terminal  onde o projeto esta sendo executado e digite `Ctrl + C` para parar.  Feito isso, execute os comandos abaixo:

```bash
# executando comando truffle version
truffle version

Truffle v5.0.36 (core: 5.0.36)
Solidity - 0.4.25 (solc-js)
Node v12.4.0
Web3.js v1.2.1

```

Agora, vamos compilar o projeto novamente. O erro que vamos gerar é porque ele não esta usando a versão do compilador pela chamado do `solc` que comentamos propositalmente.

```bash
truffle compile

Compiling your contracts...
===========================
> Compiling ./contracts/ColorDecision.sol
> Compiling ./contracts/Migrations.sol

Error: CompileError: /Users/renato/.ethereum/EthereumFinchainCourseVote/contracts/ColorDecision.sol:3:1: ParserError: Source file requires different compiler version (current compiler is 0.5.8+commit.23d335f2.Emscripten.clang - note that nightly builds are considered to be strictly less than the released version
pragma solidity ^0.4.18;
^----------------------^
,/Users/renato/.ethereum/EthereumFinchainCourseVote/contracts/Migrations.sol:1:1: ParserError: Source file requires different compiler version (current compiler is 0.5.8+commit.23d335f2.Emscripten.clang - note that nightly builds are considered to be strictly less than the released version
pragma solidity ^0.4.17;
^----------------------^

Error: Truffle is currently using solc 0.5.8, but one or more of your contracts specify "pragma solidity ^0.4.18".
Please update your truffle config or pragma statement(s).
(See https://truffleframework.com/docs/truffle/reference/configuration#compiler-configuration for information on
configuring Truffle to use a specific solc compiler version.)

Compilation failed. See above.
    at Object.compile (/usr/local/lib/node_modules/truffle/build/webpack:/packages/workflow-compile/legacy/index.js:72:1)
Truffle v5.0.36 (core: 5.0.36)
Node v12.4.0

```

```bash
 ______________________ 
< Pau controlado!!     >
 ---------------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

Volte para o arquivo `truffe-config.js`  retire os comentários das linhas, salve o arquivo e tudo ficará bem.
