#####  It features: 
- write a simple smart contract
    - setdata
    - getdata
    - log
- deploy a contract

#####  Dependence:
- babel-node
- es2017

#####  Quick Start:
- running the startDemo

``` sh
 $ cd startDemo
 $ npm install
 $ babel-node index.js
```
说明：如果本地的rpc端口是特殊的端口需要在config.js里面进行端口的修改

### 文件结构说明
```
startDemo
├── README.md
├── SimpleStartDemo.sol
├── abi_name_service_tool.js
├── cns_manager.js
├── cns_tool.js
├── codeUtils.js
├── config.js
├── index.js
├── monitor.js
├── output
│   ├── StartDemo.abi
│   ├── StartDemo.address
│   └── StartDemo.bin
├── package.json
├── post.js
├── sha3.js
├── transactionManager.js
├── transactionObject.js
├── utils.js
└── web3sync.js
```
