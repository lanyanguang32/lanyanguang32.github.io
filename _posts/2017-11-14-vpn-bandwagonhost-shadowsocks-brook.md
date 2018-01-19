# 自己动手科学上网
> 清单
- 购买vps一台（Bandwagon Host）
- 安装ShadowsocksR Server
- 安装Shadowsocks-iOS Client（brook）

## 购买一台VPS

Bandwagon Host [优惠链接](https://bwh1.net/aff.php?aff=22710&pid=56) 可以点击链接购买，价格一年200元。
购买之后进入 My Services(https://bwh1.net/clientarea.php?action=products) 点击进入 KiwiVM Control Panel 安装软件。

## 在VPS中安装ShadowsocksR Server

进入 KiwiVM Control Panel 控制台，左侧菜单 KiwiVM Extras 下面有个 ShadowsocksR Server 点击安装即可。
安装之后记得把443的端口改成8310或者其他，有些端口用的人多了，可能不能用了。然后有 Shadowsocks 客户端的下载链接和使用说明，不过ios的客户端安装比较复杂，国内appstore都下架了。

## 安装Shadowsocks-iOS Client（brook）

国内appstore下架了hadowsocks客户端，所以需要注册一个美国的账号（appstore ID）
可以参照官方的操作说明：链接(https://support.apple.com/zh-cn/HT204034), (https://support.apple.com/zh-cn/HT203905)
注意点就是先选择地区为美国，然后搜索一个免费的app(brook),点击下载提示创建新账号，这样可以选择无支付方式创建账号。
然后可以下载brook或者其他，我下载的是brook，可以用。
下好之后type选择Shadowsocks，服务器：ip:port的格式，填入密码。
然后可以自由访问自己喜欢的网站了。

## 其他

注册美国 apple ID 时需要填写一些地址信息，可以用这个网站生成 （http://www.fakenamegenerator.com/advanced.php?t=country&n%5B%5D=us&c%5B%5D=us&gen=50&age-min=35&age-max=85)
