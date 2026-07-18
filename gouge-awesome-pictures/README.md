# gouge-awesome-pictures

为中文文章自动策划并生成 16:9 白底写实 3D 极简棚拍风格的正文配图，内置 AI狗哥 作为固定主角。

## 特性

- 先输出配图策略（哪里值得画、画什么），再按指令生成
- AI狗哥 作为固定主角参与场景互动
- 白底写实 3D 极简棚拍风格，真实材质、柔和光影
- 自动质检：画幅、材质、配色、角色一致性

## 安装

在项目根目录运行：

```powershell
npx degit qq362290930-hash/gouge-awesome-pictures .trae/skills/gouge-awesome-pictures
```

重启 TRAE 即可使用。

## 目录结构

```
gouge-awesome-pictures/
├── SKILL.md                              # 主文件
├── README.md                             # 本文件
├── assets/
│   └── character-turnaround-ai-dog-bro.jpg  # AI狗哥 官方三视图
└── references/
    ├── character-sheet-ai-dog-bro.md    # AI狗哥 角色设定
    ├── visual-dna.md                    # 视觉 DNA
    ├── composition-patterns.md          # 构图模式
    ├── prompt-template.md              # 提示词模板
    └── qa-checklist.md                 # 质检清单
```

## 使用示例

对 TRAE 说：

- "帮我给这篇文章配图：`https://example.com/article`"
- "生成配图"（在已有策略后）
- "给我这篇文章重新配图"

## AI狗哥

AI狗哥是本 skill 的固定主角，由锁定三视图保证形象一致性：
- 黑色柴犬、粗黑框眼镜、半开自信眼
- 头顶双白点+中心点
- 黑色手机（右手）、左手比V

## License

MIT
