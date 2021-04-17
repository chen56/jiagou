## 

```bash
curl -X POST --data '{"jsonrpc":"2.0","method":"net_version","params":[],"id":67}'

curl -X POST -H 'Content-Type: application/json'  --data '{"jsonrpc":"2.0","method":"web3_clientVersion","params":[],"id":67}'  https://bsc-dataseed.binance.org/api/eth

curl -X POST --data '{"jsonrpc":"2.0","method":"eth_getTransactionByHash","params":["0x88df016429689c079f3b2f6ad39fa052532c56795b733da78a91ebe6a713944b"],"id":1}'


curl -X POST -H 'Content-Type: application/json'  --data '{"jsonrpc":"2.0","method":"net_version","params":[],"id":67}'  https://bsc-dataseed.binance.org/api/eth
curl -X POST -H 'Content-Type: application/json'  --data '{"jsonrpc":"2.0","method":"eth_getTransactionByHash","params":["0x88df016429689c079f3b2f6ad39fa052532c56795b733da78a91ebe6a713944b"],"id":1}'  https://bsc-dataseed.binance.org/api/eth

curl -X POST -H 'Content-Type: application/json' --data '{"jsonrpc":"2.0","method":"eth_getLogs","params":[{"topics":["0x000000000000000000000000a94f5374fce5edbc8e2a8697c15331677e6ebf0b"]}],"id":74}'  https://bsc-dataseed.binance.org/api/eth
```