# xray for Zeabur

在 Zeabur 上部署 xray 节点

## 项目特点

* 本项目用于在 Zeabur 上部署 xray ，采用的方案为 Node.js + WebSocket + VMess/Vless/Trojan/Shadowsocks + TLS
* vmess 和 vless 的 uuid 或 trojan 和 shadowsocks 的密码，路径既可以自定义，又或者使用默认值
* 部署完成如发现不能上网，请检查域名是否被墙，可使用 Cloudflare CDN 或者 worker 解决。

## 部署

* 使用自己的 GitHub 账户登录 [Zeabur](https://zeabur.com/)
* 创建一个项目
* 项目用到的变量
  | 变量名 | 是否必须 | 默认值 | 备注 |
  | ------------ | ------ | ------ | ------ |
  | UUID         | 否 | de04add9-5c68-8bab-950c-08cd5320df18 | 可在线生成 https://www.uuidgenerator.net/ |
  | VMESS_WSPATH | 否 | /vm | 以 / 开头 |
  | VLESS_WSPATH | 否 | /vl | 以 / 开头 |
  | TROJAN_WSPATH | 否 | /tr | 以 / 开头 |
  | SS_WSPATH | 否 | /ss | 以 / 开头 |
  | NEZHA_SERVER | 否 |        | 哪吒探针服务端的 IP 或域名 |
  | NEZHA_PORT   | 否 |        | 哪吒探针服务端的端口 |
  | NEZHA_KEY    | 否 |        | 哪吒探针客户端专用 Key |

* 可以使用 Zeabur 自己的二级域名，也可以使用自己的自定义域名

## 免责声明

* 本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
* 使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责.

## 赞助

爱发电：https://afdian.net/a/Misaka-blog

![afdian-MisakaNo の 小破站](https://user-images.githubusercontent.com/122191366/211533469-351009fb-9ae8-4601-992a-abbf54665b68.jpg)