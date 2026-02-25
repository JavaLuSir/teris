# 俄罗斯方块 (Tetris)

一个简单的网页版俄罗斯方块游戏。

## 运行方式

### 直接在浏览器打开
```bash
# 直接用浏览器打开 HTML 文件
# Windows:
start src\main\resources\teris.html

# Mac:
open src/main/resources/teris.html

# Linux:
xdg-open src/main/resources/teris.html
```

### 使用简单 HTTP 服务器

```bash
# Python 3
cd src/main/resources
python -m http.server 8080

# 然后访问 http://localhost:8080/teris.html
```

### 作为 Spring Boot 静态资源运行

1. 放入 Spring Boot 项目的 static 目录
2. 打包运行后访问 `http://localhost:8080/teris.html`

## 游戏操作

- **← →** 左右移动
- **↓** 加速下落
- **↑** 旋转
- **空格** 暂停

## 手机操作

屏幕下方有虚拟按钮可以操作。

## 技术栈

- 纯 HTML5 + CSS3 + JavaScript
- Canvas 绘制
- 响应式设计，支持 PC 和手机
