# 快速构建合约脚手架

### 1. install
```
$ sudo npm install -g deploy-contract-cli
```

### 2. Create Contract
deploy-contract-cli [param]
```
$ deploy-contract-cli contract-demo
```
说明：
```
command:deploy-contract-cli
项目名称：contract-demo 可以自定义为其他的名称
```

### 3. 部署和测试合约接口
操作步骤
```
$ cd contract-demo
$ npm install
$ babel-node index.js
```
### 4. 相关说明
该项目只包含了合约编译，部署，测试常用的工具库

### 5. 文件结构说明
```
contract-demo
├── README.md
├── SimpleStartDemo.sol  # 合约文件
├── abi_name_service_tool.js
├── cns_manager.js
├── cns_tool.js
├── codeUtils.js # 通用工具库
├── config.js # 通用配置
├── index.js # 部署和测试脚本
├── monitor.js
├── output  # 合约abi address bin
│   ├── StartDemo.abi
│   ├── StartDemo.address
│   └── StartDemo.bin
├── package.json
├── post.js
├── sha3.js
├── transactionManager.js
├── transactionObject.js
├── utils.js
└── web3sync.js # web3js二次封装
```
