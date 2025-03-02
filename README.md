# GISChat Notes

---

以下是一个简明的 Markdown 格式指南，帮助你使用 Quartz 进行笔记管理和同步：


# Quartz 笔记管理指南

## 初始化

1. 克隆仓库到本地：
   ```bash
   git clone git@github.com:GISChat/notes.git
   ```

2. 安装依赖：
   ```bash
   npm i
   ```

3. 创建 Quartz 项目（直接使用默认配置）：
   ```bash
   npx quartz create
   ```

## 编写笔记

1. 进入 `content` 文件夹：
   ```bash
   cd content
   ```

2. 使用 Markdown 编写笔记：
   - 创建一个新的 Markdown 文件，例如 `my-note.md`。
   - 使用 Markdown 语法编写内容。

   示例：
   ```markdown
   # 我的笔记标题

   这是一个示例笔记。

   - 列表项 1
   - 列表项 2

   **加粗文本** 和 *斜体文本*。
   ```

## 同步到 GitHub

```bash
# 同步到 GitHub，但不拉取更新，同时部署到 GitHub Pages
npx quartz sync --no-pull

```


## 配置 Quartz

1. 访问 Quartz 配置指南：
   [Quartz 配置指南](https://quartz.jzhao.xyz/setting-up-your-GitHub-repository)

2. 按照指南配置你的 GitHub 仓库，以便自动同步和部署。

## 其他资源

- [Markdown 语法指南](https://www.markdownguide.org/)
- [Quartz 官方文档](https://quartz.jzhao.xyz/)


希望这个指南对你有帮助！