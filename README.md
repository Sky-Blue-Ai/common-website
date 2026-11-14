# common-website

放一次性 / 小型静态站点的仓库，每个站点一个子目录，推上来就能通过 GitHub Pages 访问。

## 目录约定

```
/                 站点索引页（列出所有站点）
/nobel/           诺贝尔奖全表 1901–2026
```

每个站点目录都是**自包含单页**：HTML/CSS/JS/数据全在一个 `index.html` 里，无外部依赖、无构建步骤。新增站点：新建 `<name>/index.html`，然后在根 `index.html` 的列表里加一张卡片，push 即生效。

## 访问地址

https://sky-blue-ai.github.io/common-website/

（`/` 是索引页，`/nobel/` 是具体站点；GitHub Pages 需要 Source 设为 `Deploy from a branch` → `main` → `/ (root)`。）