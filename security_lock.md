# 安全锁 Security Lock

## 1\. 什么是安全锁

安全锁是云资源高危操作的二次验证服务，开启该服务后，在进行删除资源等危险操作时，需要通过手机短信校验身份，身份验证半小时内有效。之后进行危险操作需要再次验证身份。。安全锁开启状态下，您和您名下的子账号在进行某些特定操作时，需要通过手机短信验证身份，验证通过方可完成操作。

## 2\. 怎样开/关安全锁

  - 开启

进入主页控制台，找到图示安全锁开启入口，点击开启 \
![image](/images/20190712180018.png)

获取验证码后提交即完成开启操作

  - 关闭

在安全锁开启状态下，点击开关并输入验证码后，即可完成关闭操作

## 3\. 安全锁可保护哪些操作

受安全锁保护的产品类型与高危操作：

主机：开机、关机、删除实例

物理机：关机、删除实例

EIP：解绑EIP、释放EIP

共享带宽：删除实例

带宽包：删除实例

NAT网关：删除实例

内网VIP：删除实例

负载均衡 ULB：删除实例

云数据库 UDB：删除实例、关闭

运维审计系统 UHAS：关闭、删除、模拟堡垒机掉电

云内存存储 UMem：释放umemory内存

对象存储 UFile ：删除bucket、删除ufile geo buekct

归档存储 UArchive：删除实例

云硬盘 UDisk：删除实例
