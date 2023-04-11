# Siteproxy--
网页代理工具，使用 Cloudfare Worker 反向代理部分被污染的网页。
该项目主要为解决部分合法页面被雾污染的问题，请勿作他用。

部署方法：
1.注册[Cloudflare](https://dash.cloudflare.com)账号，并绑定域名。
2.创建一个 Worker 并绑定一个二级域名。
3.打开 https://raw.githubusercontent.com/Titlecan/Siteproxy--/main/worker.js 并把代码复制到 Worker。
4.光标移到 Worker 后按 Ctrl+F 搜索“ proxy.titlecan.cn ” 并替换为自己绑定了上述Worker的二级域名。

展示页面：https://siteproxy-index.titlecan.cn
体验页面:https://proxy.titlecan.cn

部分功能失效，持续修复中。



该项目改自[siteproxy](https://github.com/netptop/siteproxy)。仅保留Cloudfare Worker代理js。
