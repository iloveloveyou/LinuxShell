# Linux Shell
一些工作自己写的shell脚本，放在这里记录一下

#### 服务器远程分发文件脚本，适用于大量账户密码相同客户机分发文件
```console
./sshpass.sh
```

#### 自定义秒级循环任务，以及配套的守护脚本

```console
#循环主体脚本，无需放在定时任务内
./curl-loop.sh
#守护脚本，放在定时任务内使用
./guard_curl-loop.sh
```

#### scp自动下载，通过expect自行处理交互的问题，其实这个本质上已经不算是shell脚本了……

```console
./scp_autodown.sh
```

#### VPS自动设定定时任务

```console
./crontab.sh
```

#### curl检测指定链接返回值，若返回值非200，则自动重新拨号

```console
./checkweibo.sh
```

#### 检测php yii任务，并做失败重启

```console
./yiic.sh
```

#### 统计squid.log，计算代理请求次数和代理成功率

```console
./count-squid.sh
```

#### 一个简单的以秒为单位，循环执行任务的小脚本

```console
./loop_mission.sh
```
