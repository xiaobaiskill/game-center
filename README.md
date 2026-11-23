# 🎮 个人游戏中心（game-center）

> 个人休闲游戏中心，纯 HTML / JavaScript 实现，打开即玩、无需联网，用来打发无聊时间。

## ✅ 已支持的游戏

| name | 游戏名称 | 目录路径 | 状态 | 简介 |
| :------: | :------: | :------: | :--: | :--- |
| `snake`  | 贪吃蛇   | `games/snake/index.html`  | ✅ 可玩 | 控制小蛇吃食物，越长越快，小心撞墙和自己 |
| `tetris` | 俄罗斯方块 | `games/tetris/index.html` | ✅ 可玩 | 移动、旋转方块填满整行消除，等级越高越快 |
| `mota`   | 魔塔     | `games/mota/index.html`   | ✅ 可玩 | 三十层迷宫魔塔，有的怪能绕开，高级门要回去再开 |
| `2048`   | 2048     | `games/2048/index.html`   | ✅ 可玩 | 方块滑过去再合并，格子一样大，到 2048 后还可以继续 |
| `sudoku` | 数独     | `games/sudoku/index.html` | ✅ 可玩 | 每行、每列、每宫填入 1–9 且不重复，含简单到困难 |
| `minesweeper` | 扫雷 | `games/minesweeper/index.html` | ✅ 可玩 | 方格棋盘，按数字找地雷，第一下安全，支持初级到高级 |
| `sokoban` | 推箱子  | `games/sokoban/index.html` | ✅ 可玩 | 砖墙木箱，一百关，可撤销 |
| `dino`   | 小恐龙   | `games/dino/index.html`   | ✅ 可玩 | 彩色场景里跳跃躲避仙人掌和飞鸟，越跑越快 |
| `xiangqi` | 中国象棋 | `games/xiangqi/index.html` | ✅ 可玩 | 落点提示、走子滑动，电脑分简单、一般、困难 |

> 新增游戏时：在 `games/` 下以「内部标识」为名建立文件夹（内含 `index.html`），并在根目录 `index.html` 的游戏列表中加入对应卡片。

## 📁 目录结构

```
.
├── index.html              # 游戏中心首页（游戏列表入口）
├── games/
│   ├── snake/index.html    # 贪吃蛇
│   ├── tetris/index.html   # 俄罗斯方块
│   ├── mota/index.html     # 魔塔
│   ├── 2048/index.html     # 2048
│   ├── sudoku/index.html   # 数独
│   ├── minesweeper/index.html # 扫雷
│   ├── sokoban/index.html  # 推箱子
│   ├── dino/index.html     # 小恐龙
│   └── xiangqi/index.html  # 中国象棋
├── .gitignore
├── README.md
└── LICENSE
```

## 🚀 如何运行

直接用浏览器打开根目录下的 `index.html`，在游戏列表中选择游戏即可；
也可以直接打开 `games/<内部标识>/index.html` 进入对应游戏。
