# my-icons

自用图标库，按用途分类存放 PNG 图标，配合代理工具（Karing / SFM / Mihomo / Surge 等）使用。

## 目录结构

| 目录 | 数量 | 内容 |
|------|------|------|
| `ai/` | 17 | AI 服务图标（ChatGPT、Claude、Gemini、Grok、DeepSeek 等） |
| `liumeiti/` | 214 | 流媒体平台图标 |
| `proxy/` | 223 | 代理/机场相关图标 |
| `guoqi/` | 316 | 国旗图标 |
| `tiezhi/` | 534 | 贴纸图标 |
| `katong/` | 188 | 卡通图标 |
| `ruanjian/` | 176 | 软件图标 |
| `shenqibaobei/` | 118 | 神奇宝贝图标 |
| `shejiao/` | 101 | 社交平台图标 |
| `dibiao/` | 46 | 地标图标 |
| `emby/` | 45 | Emby 相关图标 |
| `youxi/` | 35 | 游戏图标 |
| `jichang/` | 30 | 机场图标 |
| `dog/` | 31 | 狗狗图标 |
| `jinrong/` | 25 | 金融图标 |
| `gouwu/` | 18 | 购物图标 |
| `sousuo/` | 19 | 搜索引擎图标 |
| `xinwen/` | 15 | 新闻图标 |
| `NAS/` | 3 | NAS 图标 |
| `yinyue/` | 3 | 音乐图标 |
| `youjian/` | 5 | 邮件图标 |

## 使用方式

单个图标的直链格式：

```
https://raw.githubusercontent.com/fancha0/my-icons/main/<目录>/<文件名>
```

例如 ChatGPT 图标：

```
https://raw.githubusercontent.com/fancha0/my-icons/main/ai/ai11.png
```

## 索引文件

根目录 `icons.json` 是全部图标的索引，包含每个图标的名称和直链，可被支持图标订阅的工具直接读取：

```json
{
  "name": "fancha0 图标库",
  "icons": [
    { "name": "ai1.png", "url": "https://raw.githubusercontent.com/..." }
  ]
}
```

## 说明

- 图标文件名均为编号命名（如 `liumeiti1.png`），查找具体图标请按目录浏览图片。
- 仅供个人使用，各图标版权归原品牌所有。
