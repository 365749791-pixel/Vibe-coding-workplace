[README.md](https://github.com/user-attachments/files/25740744/README.md)
# 竞品分析平台

一个完整的 Web 端竞品分析工具，支持视频上传、关键帧自动提取、横向对比和 AI 分析。

## 功能特性

✅ **竞品配置** - 支持添加多个竞品，配置版本号和平台信息
✅ **链路配置** - 内置常用链路模板，支持自定义步骤拆解
✅ **视频上传** - 支持 MP4/MOV/AVI 格式，自动提取关键帧
✅ **关键帧管理** - 可视化管理截图，支持拖拽排序和手动上传
✅ **横向对比** - 多竞品同步骤截图并排展示
✅ **AI 分析** - 自动生成对比分析内容，可手动编辑
✅ **本地存储** - 自动保存项目，支持历史记录管理

## 快速开始

直接在浏览器中打开 `index.html` 文件即可使用。

## 技术栈

- 纯 HTML + CSS + JavaScript
- 无需任何框架依赖
- 使用 localStorage 实现数据持久化
- 使用 HTML5 Video API 和 Canvas API 提取视频帧

## 部署方式

### 方式一：GitHub Pages（推荐）

1. 在 GitHub 创建新仓库
2. 推送代码到仓库
3. 在仓库设置中启用 GitHub Pages
4. 访问 `https://你的用户名.github.io/仓库名/`

### 方式二：Vercel（最快）

1. 访问 https://vercel.com
2. 导入 GitHub 仓库或直接拖拽文件夹
3. 自动部署，获得 HTTPS 链接

### 方式三：Netlify

1. 访问 https://www.netlify.com
2. 拖拽整个文件夹到 Netlify Drop
3. 立即获得可访问链接

## 使用说明

1. **新建项目** - 点击"新建分析"开始
2. **配置竞品** - 添加需要对比的产品信息
3. **配置链路** - 选择模板或自定义步骤
4. **上传视频** - 为每个竞品上传操作录屏
5. **查看分析** - 自动提取关键帧并生成对比报告

## 浏览器兼容性

- Chrome 90+
- Safari 14+
- Firefox 88+
- Edge 90+

## 许可证

MIT License
