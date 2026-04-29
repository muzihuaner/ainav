# 快点 AI 导航 - 发现最好的 AI 工具

精选 AI 工具导航网站，帮助你快速发现和访问最优质的 AI 工具。

## ✨ 功能特点

- 🔍 **智能搜索**：快速查找你需要的 AI 工具
- 🏷️ **分类筛选**：按类别和标签筛选工具
- 📱 **响应式设计**：适配各种设备
- ⚡ **轻量快速**：纯静态页面，加载速度快

## 🛠️ 技术栈

- **前端框架**：HTML5 + Tailwind CSS
- **图标库**：Lucide Icons
- **数据存储**：JSON

## 📖 使用说明

### 添加新工具

1. 访问 [提交工具](https://github.com/muzihuaner/ainav/issues)
2. 提供工具名称、描述、网址等信息
3. 等待审核通过

### 本地运行

```bash
# 直接用浏览器打开
open index.html

# 或使用本地服务器
npx serve .
```

### 数据管理

编辑 `data.json` 文件添加或修改 AI 工具信息：

```json
{
  "name": "工具名称",
  "description": "工具描述",
  "icon": "图标URL",
  "tags": ["标签1", "标签2"],
  "category": "分类",
  "url": "访问链接"
}
```

## 🤝 贡献指南

欢迎提交 Issue 或 Pull Request 来改进这个项目！

## 📄 许可证

MIT License