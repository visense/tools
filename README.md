root+自定义密码登陆，可以带上密码，如果没有填，运行时会要求输入
```bash
bash <(curl -sSL https://raw.githubusercontent.com/fscarmen/tools/main/root.sh) [PASSWORD]
```

测vps到对端经过的地区及线路，填本地IP就是测回程。如果没有填，运行时会要求输入，暂只支持 AMD64 和 ARM64 的VPS
```bash
bash <(curl -sSL https://raw.githubusercontent.com/fscarmen/tools/main/return.sh) [DESTINATION_IP]

```
端口转发，解决代理443端口被墙，本机用 127.0.0.1
```bash
bash <(curl -sSL http://www.arloor.com/sh/iptablesUtils/natcfg.sh)
```

EUserv docker、docker-compose 状态异常自动恢复，定时任务为1分钟检查一次各docker状态，菜单选择
```bash
bash <(curl -sSL https://raw.githubusercontent.com/fscarmen/tools/main/EU_docker_Up.sh)
```

docker 更换端口
```bash
bash <(curl -sSL https://raw.githubusercontent.com/fscarmen/tools/main/docker_port.sh)
```
