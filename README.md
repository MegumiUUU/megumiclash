# megumiclash
使用方法：
转换网站：https://gfwsb.114514.best/
本地转换：https://github.com/tindy2013/subconverter
远程配置设置为：https://raw.githubusercontent.com/MegumiUUU/megumiclash/master/profile.ini

部分语法：
surge_ruleset=分组,规则集链接
例如：surge_ruleset=DIRECT,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Download.list
surge_ruleset=[]方括号的后面会直接添加
例如：surge_ruleset=[]DOMAIN-SUFFIX,github.com,DIRECT

DOMAIN-SUFFIX：域名后缀匹配
DOMAIN：域名匹配
DOMAIN-KEYWORD：域名关键字匹配
IP-CIDR：IP段匹配
SRC-IP-CIDR：源IP段匹配
GEOIP：GEOIP数据库（国家代码）匹配
DST-PORT：目标端口匹配
SRC-PORT：源端口匹配
MATCH：全匹配（一般放在最后）


Add.list里面添加了部分自己特殊需求的域名
