# QuantumultX YouTube 广告跳过规则

针对 **YouTube 移动网页版**（m.youtube.com）的去广告重写规则，基于实际抓包数据编写。

## 文件说明

| 文件 | 用途 |
|------|------|
| `youtube_adblock.qxrewrite` | 远程重写规则（圈 X 直接引用此文件） |
| `youtube_no_ads.js` | 修改 YouTube player 响应体、移除广告心跳参数 |

## 导入

圈 X → 三菱按钮 → Rewrite → 引用 → 右上角+ → 粘贴：

```
https://raw.githubusercontent.com/waynekke/QuantumultX-YouTube-Adblock/main/youtube_adblock.qxrewrite
```

确保 MITM 证书已信任，hostname 会自动添加无需手动改。