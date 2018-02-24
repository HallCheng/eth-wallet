# eth-wallet
web3j Android的demo
# web3j
https://docs.web3j.io/index.html
# geth
需要先搭建一个以太坊私链,方便测试
#### 创建私链

#### geth启动参数
https://learnblockchain.cn/2017/11/29/geth_cmd_options/ 
##### 参考
geth --datadir /mnt/g/Ethereum-private --ipcdisable --port 30403 --rpcapi personal,db,eth,net,web3 --rpc --networkid 123 --rpcport 8555 --minerthreads 2 console

# web3j命令行工具
#### 编译solidity文件

 - bin Solidity二进制文件
 - abi 
 
#### 用web3j把solidity合约转成java文件

web3j solidity generate [--javaTypes|--solidityTypes] /path/to/<smart-contract>.bin /path/to/<smart-contract>.abi -o /path/to/src/main/java -p com.your.organisation.name

 