# ipfs图床

演示：https://ipf.pages.dev/

上传图片等文件到ipfs

自行修改static/file.js 第79行的API上传接口（给出的接口域名DNS被污染）

###### （API接口可以自行搭建或反向代理，搭建请看下面ipfs项目和客户端客户端，安装后运行 ipfs daemon开启节点，其中5001端口是API，8080端口是网关）
----------------------------------

![image](https://user-images.githubusercontent.com/22302606/125436780-c459352d-b684-45c3-9eb5-4579015ae99d.png)

收集的网关
```
cf-ipfs.com
183.252.17.149:82
ipfs.genenetwork.org
ipfs.fleek.co
ipfs.azurewebsites.net
ipfs.kaleido.art
ipfs.globalupload.io
ipfs.slang.cx
ipfs.adatools.io
gateway.originprotocol.com
ipfs.best-practice.se
ipfs.drink.cafe
ipfs.denarius.io        
crustwebsites.net
bin.d0x.to
ravencoinipfs-gateway.com
ipfs.smartholdem.io
infura-ipfs.io
```

### IPFS项目
https://github.com/ipfs/ipfs 

### IPFS客户端
推荐go版 https://github.com/ipfs/go-ipfs/releases
