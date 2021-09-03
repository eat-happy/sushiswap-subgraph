1、安装依赖
```shell
    yarn
```
2、进入到subgraphs/masterchef
```shell
    cd subgraphs/masterchef
```
3、生成oec subgraph.yaml
```shell
    yarn prepare:oec
```
4、codegen
```shell
    yarn codegen
```
5、build 
```shell
    yarn build
```
6、auth
```shell
graph auth https://api.hg.network/subgraph/deploy <ACCESS_TOKEN>
```
7、deploy
```shell
    yarn deploy
```

### oec.json 文件位置
subgraphs/masterchef/config/oec.json
