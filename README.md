# DirectAdmin-EnhancedSkin-Chinese
DirectAdmin enhanced skin Chinese
DirectAdmin中文汉化enhanced皮肤由梦飞科技每半年更新

支持版本directadmin Version 1.58.2 ，汉化日期为2019.09.12

使用说明：

效果一：仅中文语言包
1. 运行WINSCP,输入IP,root用户名,密码,登入服务器(出现的密钥对话框选择"是")
2. 在右边的框里面,进入/usr/local/directadmin/data/skins/enhanced/lang 目录.
3. 将en目录改名为en2.
4. 上传da中文包的目录及文件,并且取名为en
5. 完成了.

效果二：英文中文语言包，用户切换
1. 运行WINSCP,输入IP,root用户名,密码,登入服务器(出现的密钥对话框选择"是")
2. 在右边的框里面,进入/usr/local/directadmin/data/skins/enhanced/lang 目录.
3. 上传da中文包的目录及文件,并且取名为cn.
4. 完成,在用户后台可自由选择en英文模板或cn中文模板.

DirectAdmin开通默认页面修改
/usr/local/directadmin/data/templates/default/index.html

DirectAdmin打开WAF防火墙
自带了防火墙和规则自动更新，能阻挡SQL注入，XSS跨站，struts2漏洞，建站程序漏洞，0day漏洞等可识别互联网内99%的后门程序。

因本人能力有限，汉化程度只有95%左右，并且没有在对应的页面一一测试，如有翻译不当之处，敬请指出修正。

谢谢！
Jason Fan
