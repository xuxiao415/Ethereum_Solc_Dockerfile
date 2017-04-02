# Ethereum_Solc_Dockerfile
自带Solc编译器的以太坊镜像的Dockerfile

基础镜像为Ethereum/client-go:alpine, 在此基础上又安装了Solc编译器（Solidity的编译器）

## 使用方法
创建一个文件夹，将Dockerfile文件移至文件夹下，在当前文件夹下运行如下命令即可创建自带Solc编译器的以太坊开发环境
```
sudo docker build .
```
## 感谢官方提供的以太坊Docker镜像，还有Solc的Dockerfile
