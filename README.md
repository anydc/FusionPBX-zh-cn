# FusionPBX-zh-cn
FusionPBX简体中文语言包

全部为机器翻译 如有错误请谅解 

如果你有业余时间你也可以改正机器翻译错误 并联系我qq 442932427

请拉取对应的分支


### FusionPBX 系统安装的 memcached 有UDP 漏洞 需要防火墙禁止 11211 端口 否则可能被攻击导致 CPU100%

使用方法  4.4 版本

cd /var/www/fusionpbx

git clone -b 4.4 https://github.com/xuntee/FusionPBX-zh-cn tmp

\cp -rf tmp/* .

rm -rf tmp

git reset --hard HEAD



