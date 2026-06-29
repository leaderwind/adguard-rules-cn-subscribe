# AdGuard Rules CN Subscribe

面向中文用户的 AdGuard 公开订阅仓库。规则由私有维护仓库完成上游获取、分层、去重、审核和生成，本仓库只发布最终 `dist/` 与订阅说明。

规则约每小时自动更新。

## 推荐订阅

### Android

主规则：

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-android.txt?v=1
```

DNS：

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-dns.txt?v=1
```

### Windows / macOS

主规则：

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-windows.txt?v=1
```

DNS：

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-dns.txt?v=1
```

### Browser

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-browser.txt?v=1
```

### AdGuard Home / AdGuard DNS

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-dns.txt?v=1
```



## 待审查规则（AI 尚未审查的新规则）

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-pending-review.txt?v=1
```

## 其他分层订阅

Network：

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-network.txt?v=1
```

Content：

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-content.txt?v=1
```

Scriptlet：

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-scriptlet.txt?v=1
```

Conservative：

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-conservative.txt?v=1
```

Aggressive：

```text
https://raw.githubusercontent.com/leaderwind/adguard-rules-cn-subscribe/main/dist/adguard-aggressive.txt?v=1
```

本仓库不接收日志、候选规则或未经审核的自定义规则。

订阅地址使用稳定接口版本 `v=1`。规则文件中的 `! Version` 是每次生成的构建版本，用于确认规则是否已经更新。
