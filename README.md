# Blog

用纯 GitHub Markdown 维护的个人博客仓库。

不使用任何博客框架，不依赖构建流程，直接把仓库当作内容库来写、读、整理和归档。

## 这是什么

这是一个尽量轻、尽量稳的个人博客实验。

我希望它满足几件事：

- 打开 GitHub 仓库就能直接阅读
- 不需要额外的站点框架和渲染流程
- 所有文章都是普通 Markdown 文件
- 目录长期可维护，迁移成本低

## 导航

- [文章索引](./index.md)
- [归档](./archive.md)
- [标签](./tags.md)
- [关于](./about.md)
- [系列文章](./series/README.md)
- [写作模板](./templates/post.md)
- [发布检查清单](./templates/publish-checklist.md)

## 目录结构

```text
blog/
├─ README.md
├─ index.md
├─ about.md
├─ archive.md
├─ tags.md
├─ templates/
│  └─ post.md
├─ posts/
│  ├─ 2026/
│  └─ 2025/
├─ series/
├─ notes/
└─ assets/
   ├─ images/
   └─ files/
```

## 每个目录的用途

- `README.md`：仓库首页，放博客说明和主要入口。
- `index.md`：文章总索引，适合按时间倒序维护。
- `about.md`：个人介绍、写作主题、联系方式。
- `archive.md`：归档页，按年份或月份汇总。
- `tags.md`：标签页，手动维护每个标签下的文章。
- `templates/`：文章模板和系列模板。
- `posts/`：正式发布的文章，按年份分目录。
- `series/`：系列文章目录，每个系列一个子目录。
- `notes/`：灵感、草稿、临时记录，不算正式发布。
- `assets/images/`：图片资源。
- `assets/files/`：附件、示例文件、下载资源。

## 你可以怎么读这个仓库

- 想看最新内容：先看 [文章索引](./index.md)
- 想按年份找文章：看 [归档](./archive.md)
- 想按主题找文章：看 [标签](./tags.md)
- 想连续读某个主题：看 [系列文章](./series/README.md)
- 想开始自己写：看 [文章模板](./templates/post.md)

## 文件命名规则

推荐统一使用：`YYYY-MM-DD-slug.md`

例如：

- `2026-03-22-github-markdown-blog.md`
- `2026-03-25-git-workflow-notes.md`
- `2026-04-01-how-i-write-notes.md`

命名约定：

- 日期使用 `YYYY-MM-DD`，方便排序和归档。
- 文件名正文部分使用小写英文或拼音。
- 单词之间使用 `-`，不要使用空格。
- 不建议在文件名里混用中文、空格和特殊字符。
- 文章标题可以在 Markdown 正文里正常写中文。

推荐做法：

- 文件名保持稳定、可迁移、可排序。
- 正文第一行使用真正的文章标题。
- 图片文件名也尽量使用英文或拼音，例如 `git-workflow-overview.png`。

## 推荐写作流程

```text
ideas -> drafts -> posts -> index/archive/tags -> series
```

对应到这个仓库：

1. 在 `notes/ideas.md` 记下想法
2. 在 `notes/drafts/` 写草稿
3. 发布到 `posts/年份/`
4. 更新 `index.md`、`archive.md`、`tags.md`
5. 如果是系列内容，再更新 `series/`

## 写作流程

1. 先在 `notes/` 记录想法或草稿。
2. 正式发布时，将文章放入 `posts/年份/`。
3. 在 `index.md`、`archive.md`、`tags.md` 中补充链接。
4. 如果是系列文章，再同步更新 `series/` 下对应系列说明。

## 最新文章

目前已经有一篇示例文章，可以直接参考：

- [从零开始搭一个纯 Markdown 博客](./posts/2026/2026-03-22-start-a-pure-markdown-blog.md)
- [文章模板](./templates/post.md)

## 当前系列

- [从零搭建纯 Markdown 博客](./series/pure-markdown-blog/README.md)

## 快速开始

如果你今天就想开始写，可以按这个顺序：

1. 打开 `notes/ideas.md` 记下 3 个想写的主题
2. 复制 `templates/post.md` 到 `notes/drafts/`
3. 写完后，把文章移到 `posts/2026/`
4. 按 `templates/publish-checklist.md` 补全索引和标签

## 后续建议

- 第一篇文章发布后，先补 `index.md` 和 `archive.md`。
- 如果以后文章变多，可以为 `series/` 下的每个系列增加单独的 `README.md`。
