# 网页游戏集合

包含多个经典网页小游戏。

## 游戏列表

1. **俄罗斯方块** - teris.html
2. **吃豆子** - pacman.html

## 运行方式

### 直接在浏览器打开

```bash
# Windows:
start src\main\resources\teris.html    # 俄罗斯方块
start src\main\resources\pacman.html   # 吃豆子

# Mac:
open src/main/resources/teris.html
open src/main/resources/pacman.html

# Linux:
xdg-open src/main/resources/teris.html
xdg-open src/main/resources/pacman.html
```

### 使用简单 HTTP 服务器

```bash
# Python 3
cd src/main/resources
python -m http.server 8080

# 然后访问:
# http://localhost:8080/teris.html  (俄罗斯方块)
# http://localhost:8080/pacman.html (吃豆子)
```

## 游戏操作

### 俄罗斯方块
- **← →** 左右移动
- **↓** 加速下落
- **↑** 旋转
- **空格** 暂停

### 吃豆子
- **↑ ↓ ← →** 或 **WASD** 移动
- **空格** 暂停

## 手机操作

屏幕下方有虚拟按钮可以操作。

## 技术栈

- 纯 HTML5 + CSS3 + JavaScript
- Canvas 绘制
- 响应式设计，支持 PC 和手机
