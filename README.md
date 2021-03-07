# NRSC


特别声明
<br/>
近期网络上反映的《某*环智能合约》，不是本公司的产品。大家不要听信谣言，谨防上当受骗。
如遇财产损失，建议大家及时报警。
本公司也保留相关法律权利。
<br/>
如有其它开发技术研发类产品需求或合作，请加微信，谢谢!
<br/>
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/103817_7b314e6f_6502830.png "1615081623.png")
<br/>

江西至融软件有限公司<br/>
2021-3-7


### Building the source

```
git clone https://github.com/nrsc2020/nrsc.git
cd nrsc
cargo build
```

See [Building the source](https://github.com/nrsc2020/nrsc/docs/blob/master/build/README.md) for more information

### Docker quick start

```
docker pull registry.cn-beijing.aliyuncs.com/nrsc/nrsc_testnet_dev:latest
docker run --rm -d --name nrsc -p 6615:6615 -p 8080:8080 registry.cn-beijing.aliyuncs.com/nrsc/nrsc_testnet_dev
```

See [Docker quick start](https://github.com/nrsc2020/nrsc/docs/blob/master/start-docker/README.md) for more information

### License

NRSC is released under the terms of the LGPL-3.0 license. See [COPYING](COPYING) for more information or see https://opensource.org/licenses/LGPL-3.0
