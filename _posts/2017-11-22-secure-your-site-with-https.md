# HTTPS加密网站

HTTPS加密网站已经成为标配。商业的证书也不算贵，而且个人创业者还有免费方案可选。

> 清单
- 域名一个 & 主机ECS
- Let's Encrypt 免费证书申请
- 一键安装

## 域名一个 & 主机ECS

网站嘛域名主机少不了。先将域名解析到主机ip地址，安装webserver & nginx。

## Let's Encrypt 免费证书申请

[Let's Encrypt](https://letsencrypt.org/getting-started/)

[SETP BY SETP](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04)

[Secure your site with HTTPS](https://support.google.com/webmasters/answer/6073543?hl=en)

## 一键安装

可以使用 [certbot](https://certbot.eff.org/) 自动安装/免费续签证书 

## 其他

Let's Encrypt 有效期90天可以通过定时任务自动续签