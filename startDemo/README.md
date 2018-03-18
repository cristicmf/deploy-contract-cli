#####  It features: 
快速搭建开发合约项目：
```
- 包含合约测试实例
- 包含部署合约，开发合约，编译合约通用库
```

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
├── SimpleStartDemo.sol       # 合约
├── abi_name_service_tool.js  
├── cns_manager.js
├── cns_tool.js
├── codeUtils.js              # 通用工具库 
├── config.js                 # 通用配置
├── index.js                  # 编译合约、部署合约、测试合约
├── monitor.js
├── output                    # 合约abi、合约address、合约bin
│   ├── StartDemo.abi
│   ├── StartDemo.address
│   └── StartDemo.bin
├── package.json
├── post.js
├── sha3.js
├── transactionManager.js
├── transactionObject.js
├── utils.js
└── web3sync.js               # web3js二次封装
```
