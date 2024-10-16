# heminet
heminet命令
### 使用pm2启动
```
export POPM_BTC_PRIVKEY=<>
export POPM_STATIC_FEE=300
export POPM_BFG_URL=wss://testnet.rpc.hemi.network/v1/ws/public
pm2 start ./heminetwork/bin/popmd --name heminet
```
### 查询状态
[查询状态](https://testnet.popstats.hemi.network/pubkey/02CC78498CE91BA7299210B945AF54808EFF716D792EE25ACDFA914D793EB6B799.html)
### 升级
```
cd /root/heminetwork/
git pull
```
