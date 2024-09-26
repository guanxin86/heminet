# heminet
heminet命令
### 使用pm2启动
```
export POPM_BTC_PRIVKEY=<>
export POPM_STATIC_FEE=300
export POPM_BFG_URL=wss://testnet.rpc.hemi.network/v1/ws/public
pm2 start ./heminetwork/bin/popmd --name heminet
```
