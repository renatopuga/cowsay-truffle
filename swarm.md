# swarm 

## Censorship resistant storage and communication infrastructure for a sovereign digital society.

* https://swarm-gateways.net/

Agora, faça download do Swarm 64 bits:

* https://ethswarm.blob.core.windows.net/builds/swarm-linux-amd64-0.5.4-7758fb23.tar.gz

```bash
# volte para o seu home
cd ~

# download do swarm-linux 64bits
wget -c https://ethswarm.blob.core.windows.net/builds/swarm-linux-amd64-0.5.4-7758fb23.tar.gz

# descompactar o swarm
tar -zxvf swarm-linux-amd64-0.5.4-7758fb23.tar.gz

# entrar dentro do diretorio do swarm
cd swarm-linux-amd64-0.5.4-

# listar os diretorios
ls -l
-rw-rw-r-- 1 ethereum-fiap ethereum-fiap    32397 Nov 29 10:22 COPYING
-rwxrwxr-x 1 ethereum-fiap ethereum-fiap 58989239 Nov 29 10:24 swarm

# move o executavel para /usr/local/bin
sudo cp swarm /usr/local/bin

# agora, execute o comando swarm
swarm 
INFO [12-07|14:32:50.926] Maximum peer count                       ETH=50 LES=0 total=50
INFO [12-07|14:32:50.926] You don't have an account yet. Creating one... 
Your new account is locked with a password. Please give a password. Do not forget this password.
Passphrase: 
Repeat passphrase: 
Unlocking swarm account 0x1B8a338d70f51b9F095A7bAb6b423A4082975f84 [1/3]
Passphrase: 
INFO [12-07|14:34:31.263] Starting peer-to-peer node               instance=swarm/v0.5.4-7758fb23/linux-amd64/go1.13.4
INFO [12-07|14:34:31.331] New local node record                    seq=1 id=4eacfd229d21656e ip=127.0.0.1 udp=30399 tcp=30399
INFO [12-07|14:34:31.331] Updated bzz local addr                   oaddr=87b4e920c4b9d1f635e3e479a9af78c53cff62ab5e6e069b42ec73f56dac54b5 uaddr=enode://06a9af15ce169358717040d9f60d07bf2e6484ae6e59704df5ed21e808653aa5802454baa49930339ef2768e97aa013bbdc3f0912fba2c9c8f99159cefd9cc59@127.0.0.1:30399
INFO [12-07|14:34:31.331] Starting bzz service 
INFO [12-07|14:34:31.331] Starting hive                            baseaddr=87b4e920
INFO [12-07|14:34:31.331] Detected an existing store. trying to load peers 
INFO [12-07|14:34:31.331] hive 87b4e920: no persisted peers found 
INFO [12-07|14:34:31.331] Swarm network started                    bzzaddr=87b4e920c4b9d1f635e3e479a9af78c53cff62ab5e6e069b42ec73f56dac54b5
INFO [12-07|14:34:31.331] bzzeth starting... 
INFO [12-07|14:34:31.331] Starting outbox 
INFO [12-07|14:34:31.331] Started Pss 
INFO [12-07|14:34:31.331] Loaded EC keys                           pubkey=04a91c456554f2bc921ac9aaef84c557d839f46ad03509d44969391cd20549bf47ea163ef8e876615d459a812b38fba2983eb383b29f0796207cd46c26de80e429 secp256=03a91c456554f2bc921ac9aaef84c557d839f46ad03509d44969391cd20549bf47
INFO [12-07|14:34:31.332] starting bzz-retrieve                    base=87b4e920c4b9d1f6
INFO [12-07|14:34:31.332] IPC endpoint opened                      url=/home/ethereum-fiap/.ethereum/bzzd.ipc
INFO [12-07|14:34:31.333] Started P2P networking                   self=enode://06a9af15ce169358717040d9f60d07bf2e6484ae6e59704df5ed21e808653aa5802454baa49930339ef2768e97aa013bbdc3f0912fba2c9c8f99159cefd9cc59@127.0.0.1:30399
INFO [12-07|14:34:31.333] Starting Swarm HTTP proxy                port=8500
WARN [12-07|14:36:39.414] Served eth_coinbase                      reqid=3 t=8.836µs err="the method eth_coinbase does not exist/is not available"
WARN [12-07|14:36:39.415] Served eth_blockNumber                   reqid=4 t=6.371µs err="the method eth_blockNumber does not exist/is not available"

```

**Abra uma nova aba de terminal...**

```bash
geth attach /home/ethereum-fiap/.ethereum/bzzd.ipc
INFO [12-07|14:36:39.227] Bumping default cache on mainnet         provided=1024 updated=4096
WARN [12-07|14:36:39.228] Sanitizing cache to Go's GC limits       provided=4096 updated=2659
Welcome to the Geth JavaScript console!

 modules: accounting:1.0 admin:1.0 bzz:1.0 debug:1.0 hive:1.0 pss:1.0 rpc:1.0 swarmfs:1.0 web3:1.0

> 
```

```bash
 _________________________________________
/ Agora chame o cara da fiap para liberar \
\ sei lá o que!                           /
 -----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

```


