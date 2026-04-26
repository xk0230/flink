# Python 3D 贪吃蛇网站

这是一个基于 **Flask + Three.js** 的网页小游戏项目，主页可以直接玩 3D 贪吃蛇。

## 运行方式

```bash
cd python-3d-snake
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

然后打开浏览器访问：

- http://127.0.0.1:5000/

## 操作说明

- `W / A / S / D`：前后左右
- `Q / E`：向上 / 向下
- `R`：失败后重开

## 玩法规则

- 吃到红色食物，蛇身变长并加分。
- 撞到自己身体即游戏结束。
- 穿过边界会从另一侧出现（环形空间）。
