# heminet
heminet命令
### 使用pm2启动
```
pm2 start ./popmd --name heminet \
--env POPM_BTC_PRIVKEY=<> \
--env POPM_STATIC_FEE=300 \
--env POPM_BFG_URL=wss://testnet.rpc.hemi.network/v1/ws/public
```
