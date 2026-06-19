# MVERI Homepage

这是一个静态首页页面，页面入口是 `index.html`。

## 查看页面效果

推荐使用本地静态服务查看页面效果：

```bash
npm start
```

启动成功后，浏览器打开：

```text
http://localhost:3000/
```

也可以直接在浏览器中打开仓库根目录下的 `index.html` 文件。

## 页面内容

- 顶部品牌 Logo、导航菜单、语言切换入口
- 首页主视觉文案与两个行动按钮
- 右侧质量框架卡片和蓝色金字塔视觉
- 三个核心优势卡片
- 深蓝色页脚

## 文件说明

- `index.html`：页面结构和内联样式
- `server.js`：零依赖 Node 静态文件服务器
- `package.json`：提供 `npm start` 启动脚本
