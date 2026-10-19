# 心灵探索 · 心理测试

这是一个无需注册或付费服务器的单页中文互动心理测试网站。

## 功能

- 保留原始 12 道题目及各题选项。
- 每题为单选；全部 12 题答完才能提交。
- 完成后显示各题选择汇总及 A/B/C/D 选择数量。
- 适用于手机、平板、电脑。
- 支持修改答案、复制或保存测试结果。

## 免费公开发布（GitHub Pages）

仓库： https://github.com/josh1638/xinling-test

1. 打开 https://github.com/josh1638/xinling-test/settings/pages
2. 在 **Build and deployment** 的 **Source** 选择 **Deploy from a branch**。
3. 选择 **Branch: main** 和 **Folder: / (root)**，点击 **Save**。
4. 到 **Actions** 查看 `pages build and deployment` 工作流程是否成功。
5. 公开网址： https://josh1638.github.io/xinling-test/

请注意：在 GitHub Pages 配置和构建成功前，上述公开网址可能无法访问。

## 技术

所有页面样式与交互脚本均包含在 `index.html`，不需要后端、数据库或第三方接口。答题记录仅在访客的浏览器中操作，不会自动传送给站长。
