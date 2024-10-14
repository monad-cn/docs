
# Monad 官网中文版

本项目旨在将 [Monad 的官方网站](https://docs.monad.xyz/)内容翻译成中文，以便更多的中文用户能够更好地理解和使用 Monad 的相关信息。


## 翻译目标

- **翻译内容**：将 Monad 官网的所有相关内容（包括文档、指南、技术细节等）翻译成中文。
- **保持一致性**：确保翻译内容准确、专业，并与原文保持一致。
- **提升可读性**：使用流畅的中文表达，使中文用户能够轻松理解。


## 项目结构

- **readme.md**：项目说明。
- **SUMMARY.md**：gitbook 章节目录。
- **content**：翻译的文章内容。
- **book.json**：gitbook 配置文件。


## 参与贡献

我们欢迎任何对项目感兴趣的开发者、翻译者和技术爱好者参与贡献！如果您想为翻译项目做贡献，请遵循以下步骤：

1. `Fork` 这个仓库。
2. 创建一个新的分支并进行翻译工作。
3. 提交您的更改并发起 `Pull Request`。


## 使用 GitBook 本地启动

可以在本地启动 `gitbook` 检查翻译内容和排版，请按照以下步骤操作：

1. 安装 `gitbook cli`

首先确保您已安装 [Node.js](https://nodejs.org/)。然后，使用以下命令全局安装：

```bash
npm install -g gitbook-cli
```

2. 安装依赖

```bash
gitbook install
```

注意：可以因为有的插件不支持你的`node`版本，如果报错可以选择使用`node 10.x`，重新安装`gitbook-cli`后重试。

3. 本地启动

```bash
gitbook build
gitbook serve
```

打开浏览器并访问 http://localhost:4000，将能够查看本地文档。


## 联系我们

如果您对本项目有任何问题或建议，请随时联系我(微信: `xxxfu`, 邮箱: `smallfu666@gmail.com`)。感谢您的支持和参与！

