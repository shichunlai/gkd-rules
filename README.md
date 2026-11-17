# shichunlai/gkd-rules

## 声明

**1. 本仓库的源码几乎来自GKD的官方或第三方的复刻，仅供本人学习使用，其他人的任何行为与本人无关。**

**2. 本仓库的订阅链接仅作为下载或更新订阅文件，绝不会收集任何用户的任何信息。**

**3. 本仓库的订阅链接是本人学习研发，不得以任何形式的转发、发布、传播、以及展示。**


## 订阅

> 在 GKD App 里 **主页 → 订阅 → 右上角 + → 粘贴链接**。某个源下载失败就换下一个。

### 方案一：国内 GitHub 镜像（最稳 · 推荐先试）

```txt
https://raw.gitmirror.com/shichunlai/gkd-rules/main/dist/gkd.json5
```

### 方案二：jsDelivr CDN（GKD 官方也在用）

```txt
https://fastly.jsdelivr.net/gh/shichunlai/gkd-rules@main/dist/gkd.json5
```

### 方案三：jsDelivr 备用节点（GKD App 对某些 CDN 域名敏感时用）

```txt
https://gcore.jsdelivr.net/gh/shichunlai/gkd-rules@main/dist/gkd.json5
```

### 方案四：GitHub Raw（兜底 · 国内可能被墙）

```txt
https://raw.githubusercontent.com/shichunlai/gkd-rules/main/dist/gkd.json5
```

### 方案五：npmmirror 源（发了 npm 包才可用）

```txt
https://registry.npmmirror.com/gkd-rules-scl/latest/files/dist/gkd.json5
```

### 手机上 GKD 下载失败怎么办？

如果浏览器能打开链接但 GKD 报"下载失败"：

1. **先换一个源**（上面 5 个一个个试），大概率其中一个能用
2. **检查 GKD 版本**：设置 → 关于 → 至少 v1.10+，太老的版本 TLS/HTTP2 支持有问题
3. **手机浏览器直接访问**：把链接贴到手机浏览器里打开，如果手机浏览器也打不开 → 你当前网络屏蔽了该域名，换 Wi-Fi / 关 VPN 再试
4. **关闭系统代理 / VPN**：某些 VPN 会劫持 Cloudflare 的 TLS 握手，导致 GKD 下载失败但浏览器正常
5. **手机上没有 Magic**：GitHub Raw 大概率下不来，优先用 gitmirror 或 jsDelivr

##

当前版本: v8

当前订阅文件已适配 689 个应用，共有 1475 应用规则组，3 全局规则组

## 相关

在 [GKD官网](https://gkd.li/) 查看 [GKD基础使用教程](https://gkd.li/guide/) 、[常见问题](https://gkd.li/guide/faq) 以及 [API说明](https://gkd.li/api/)

查看 [规则编写教程](https://github.com/Snoopy1866/blogs/blob/main/software/gkd/gkd-rule-tutorial/gkd-rule-tutorial.md) 使用 [GKD订阅模板](https://github.com/gkd-kit/subscription-template) 快速构建自己的订阅

## 感谢以下项目贡献

本仓库使用 [AIsouler](https://github.com/AIsouler/GKD_subscription) 构建的订阅同步为主

[gkd-kit/subscription](https://github.com/gkd-kit/subscription)

查看 [GKD基础使用、规则编写教程](https://github.com/Snoopy1866/blogs/tree/main/software/gkd) By [@Snoopy1866](https://github.com/Snoopy1866)

如何编写订阅/贡献此项目 -> [CONTRIBUTING.md](./CONTRIBUTING.md)
