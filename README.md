# 🎮 个人游戏中心（game-center）

> 个人休闲游戏中心，纯 HTML / JavaScript 实现，打开即玩、无需联网，用来打发无聊时间。

## ✅ 已支持的游戏

| name | 游戏名称 | 目录路径 | 状态 | 简介 |
| :------: | :------: | :------: | :--: | :--- |
| `snake`  | 贪吃蛇   | `games/snake/index.html`  | ✅ 可玩 | 控制小蛇吃食物，越长越快，小心撞墙和自己 |
| `tetris` | 俄罗斯方块 | `games/tetris/index.html` | ✅ 可玩 | 移动、旋转方块填满整行消除，等级越高越快 |
| `mota`   | 魔塔     | `games/mota/index.html`   | ✅ 可玩 | 勇者闯魔塔，收集钥匙装备、精打细算攻防血，登顶击败魔王 |

> 新增游戏时：在 `games/` 下以「内部标识」为名建立文件夹（内含 `index.html`），并在根目录 `index.html` 的游戏列表中加入对应卡片。

## 📁 目录结构

```
.
├── index.html              # 游戏中心首页（游戏列表入口）
├── games/
│   ├── snake/index.html    # 贪吃蛇
│   ├── tetris/index.html   # 俄罗斯方块
│   └── mota/index.html     # 魔塔
├── README.md
└── LICENSE
```

## 🚀 如何运行

直接用浏览器打开根目录下的 `index.html`，在游戏列表中选择游戏即可；
也可以直接打开 `games/<内部标识>/index.html` 进入对应游戏。
