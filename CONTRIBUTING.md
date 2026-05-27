# Contributing to QianQIUlp

感谢你对本项目的关注！这个仓库承载了我的 GitHub 个人主页 README 以及相关的主页资源。如果你发现这里的内容有错别字、链接失效、或者有关于新颖组件的建议，非常欢迎提交贡献！

## 🛠️ 怎么在本地预览与测试修改?

本仓库主要由 `README.md` 和静态资产构成。本地开发和验证非常简单：

1. **克隆仓库**：
   ```bash
   git clone https://github.com/QianQIUlp/QianQIUlp.git
   cd QianQIUlp
   ```
2. **本地预览**：
   - 推荐使用 VS Code 打开项目，并安装 `Markdown Preview Enhanced` 或自带的 Markdown 预览工具进行可视化预览。
   - 也可以将修改后的 `README.md` 内容贴入你个人账号的测试 Profile 仓库中进行在线实际效果校验。
3. **资产管理**：
   - 所有的个人照片或插图均需放入 `assets/images/` 目录下。
   - 请在引用资产时使用相对路径或 GitHub 的 Raw 地址，确保加载稳定。

## 📝 Commit message 怎么写?

本项目遵循 [Conventional Commits](https://www.conventionalcommits.org/)（约定式提交）规范。每次提交的代码应当有清晰、结构化的提交信息，以确保 Changelog 能够被清晰生成。

格式如下：
```text
<type>(<scope>): <subject>
```

常用 `<type>` 类型：
- `docs`: 文档/内容更新（如更新 README、徽章、修改个人介绍等）
- `feat`: 新增特性/新模块（如主页新增统计卡片或第三方 widget）
- `fix`: 修复 Bug（如修复布局拉伸、失效的外链或无效的徽章地址）
- `chore`: 日常事务、辅助文件等微调（如更新配置文件、.gitignore）

示例：
- `docs(readme): update bilibili profile link`
- `fix(readme): fix badge image loading error`

## 🔀 PR 流程是什么?

1. **创建分支**：从 `main` 分支切出一个专属的修改分支：
   ```bash
   git checkout -b docs/update-readme-info
   ```
2. **提交与推送**：在本地调整好 Markdown 格式并检查链接无误后，将代码推送到你的远程分支。
3. **发起 Pull Request**：
   - 目标分支选择 `main`。
   - 填写 PR 模板（会自动载入），简要描述修改内容和原因。
   - 如果解决了某个已有的 Issue，请在描述中写明 `Closes #编号`。
4. **等待 Review**：我会尽快审核你的 PR，在确认无误后会将其合并入主分支。
