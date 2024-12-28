# Web Content Extractor

基于 AI 驱动的网页内容提取工具，能够智能识别和提取网页的核心内容，为 AI 模型提供清晰的输入数据。

## 🌟 特点

- 🤖 智能内容提取：自动识别网页主要内容，提取正文、标题和摘要
- 🧹 清理干扰元素：自动移除广告、导航栏等无关内容
- 🚀 简单易用的 API：提供 RESTful API 接口，支持批量处理
- 💻 现代化 UI：简洁优雅的用户界面，良好的响应式设计

## 🛠️ 技术栈

- **Frontend**:
  - Next.js 14
  - React
  - Tailwind CSS
  - TypeScript
  - Lucide Icons

- **Backend**:
  - Next.js API Routes
  - Readability.js
  - Puppeteer

## 🚀 快速开始

1. 克隆项目
```bash
git clone https://github.com/eggacheb/web-content-extractor.git
cd web-content-extractor
```

2. 安装依赖
```bash
npm install
```

3. 启动开发服务器
```bash
npm run dev
```

4. 打开浏览器访问 [http://localhost:3000](http://localhost:3000)

## 📚 API 使用

### 提取网页内容

```http
GET /api/extract?url=https://example.com
```

#### 响应示例

```json
{
  "title": "文章标题",
  "content": "文章正文内容...",
  "excerpt": "文章摘要",
  "byline": "作者信息（如果有）"
}
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License - 查看 [LICENSE](LICENSE) 文件了解更多信息。

## 🔗 在线演示

访问 [https://web-content-extractor.vercel.app](https://web-content-extractor.vercel.app) 体验在线版本。
