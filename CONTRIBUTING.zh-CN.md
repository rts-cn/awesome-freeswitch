# 投稿指南

[English](CONTRIBUTING.md) | 简体中文

感谢帮忙维护这份清单。

## 收录标准

- 与 FreeSWITCH 相关，并且现在能实际使用。
- 有可访问的官方页面或代码仓库。
- 有明确的开源许可证，或提供可试用版本。
- 不接受纯广告、长期停更、已经无法访问的项目。

条目失效时**不要删除它**，请移到 [过时](README.zh-CN.md#过时) 区，这样别处指向它的链接仍然有效，读者也能知道它曾经存在。

## 条目格式

每种语言一个文件：`README.md` 是英文，`README.zh-CN.md` 是简体中文。新增或修改条目时，**两份文件都要改**。链接文本用项目名，不要用裸 URL。

```markdown
- [eslgo](https://github.com/percipia/eslgo) - Go 语言的 Event Socket 客户端，支持 inbound 和 outbound 两种模式，事件带类型。 `MPL-2.0` `Go`
```

- **名称**：项目公开使用的正式写法。
- **描述**：用一两句话说清它是什么、解决什么问题，不要堆形容词。
- **标签**：`许可证` `主语言`，用反引号，放在描述末尾；两份文件里都要写。只写能核实的那一项，只写一个或留空都可以。
- **标签来源**：取自项目仓库页面的公开信息，识别不出就留空，不要猜。

## 新增语言

新增语言前请先确认两件事：确实有该语种的读者（可看仓库 Insights 的 referrers），并且有母语维护者愿意长期校对。两条缺一条，译文的错误就会一直留在页面上。

## 提交方式

提一个 [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)，说明新增或修改了哪一条。

还没有完整的投稿流程文档，可以先参考 [awesome-go 的贡献指南](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md)。
