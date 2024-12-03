# synology_deny-ip-list
一个爆破群晖(DSM)登录密码的黑名单IP地址库（仅含中国IP），国外的IP地址不需要，因为可以在群晖的防火墙里面设置仅允许中国IP地址访问，所以只需要屏蔽国内的恶意IP地址就可以了。

# 免责声明：
本项目中的所有IP地址来自本人群晖的自动封锁功能的封锁数据库，封锁的内容包括恶意登录DSM，MailPlus-Server等服务。本人仅作搬运。 任何人使用本项目中的数据请自行承担风险，本人不对使用此项目中数据承担任何责任。

# 使用方法：
打开控制面板->安全性->防护->启用自动封锁，允许/封锁黑名单，封锁名单，新增，导入IP地址黑名单
![Image](https://raw.githubusercontent.com/ohyeah521/synology_deny-ip-list/main/pic/usage.jpg)


# 防火墙配置，仅允许中国IP访问
![Image](https://raw.githubusercontent.com/ohyeah521/synology_deny-ip-list/main/pic/firewall.jpg)

