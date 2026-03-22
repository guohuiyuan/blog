# 系列文章

这里存放系列文章。

建议做法：

- 每个系列一个子目录
- 每个系列目录放一个 `README.md` 作为导读
- 系列内文章仍然保持清晰编号

## 当前系列

- [从零搭建纯 Markdown 博客](./pure-markdown-blog/README.md)

示例：

```text
series/
└─ ai-coding/
   ├─ README.md
   ├─ 01-why-i-started-this-series.md
   └─ 02-tooling-choice.md
```

## 维护建议

- 系列首页写清楚主题、目标读者和阅读顺序
- 单篇文章名称可以使用 `01-xxx.md`、`02-xxx.md` 这种编号方式
- 如果系列文章同时也属于正式文章，可以在 `posts/` 里保留主入口，再在系列页聚合链接
*** Add File: series/pure-markdown-blog/README.md
# 从零搭建纯 Markdown 博客

这个系列记录如何用最轻量的方式维护个人博客：

- 不用框架
- 不依赖构建流程
- 直接使用 GitHub 仓库阅读和管理

## 适合谁

- 想先开始写，而不是先折腾技术栈的人
- 想把内容文件长期保留、方便迁移的人
- 喜欢简单目录和手动维护索引的人

## 阅读顺序

- [01 从零开始搭一个纯 Markdown 博客](./01-start-a-pure-markdown-blog.md)
- [02 如何维护索引、归档和标签](./02-maintain-index-archive-and-tags.md)

## 这个系列会写什么

- 为什么选择纯 Markdown
- 目录怎么规划
- 文件怎么命名
- 如何维护归档、标签和系列页
- 内容多起来后，什么时候再考虑升级工具
