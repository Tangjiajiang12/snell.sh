# 感谢XZChen。
# 此脚本仅用于远程连接家中局域网内机器，请勿用于任何非法行为！（适用于64位Linux系统）。
# 运行完毕后屏幕显示psk，默认端口号443，按照标准填入Surge即可。
# 请使用root用户运行。

1.1 Debian & Ubuntu 用户请运行：

```
wget --no-check-certificate -O snell.sh https://raw.githubusercontent.com/Tangjiajiang12/snell.sh/master/snell.sh
chmod +x snell.sh
./snell.sh
```

1.2 Centos & RedHat 用户请运行：

```
wget --no-check-certificate -O snell.sh https://raw.githubusercontent.com/Tangjiajiang12/snell.sh/master/snell.sh
chmod +x snell.sh
./snell.sh
```

1.3 首次安装默认端口号443，如需修改请
在所有脚本运行结束后运行.自行修改：

```
nano /etc/snell/snell-server.conf
systemctl restart snell
```

1.4 查看运行状态：

```
systemctl status snell
```

1.5 卸载方法：

```
wget --no-check-certificate -O uninstall-snell.sh https://raw.githubusercontent.com/Tangjiajiang12/snell.sh/master/uninstall-snell.sh
chmod +x uninstall-snell.sh
./uninstall-snell.sh
```
