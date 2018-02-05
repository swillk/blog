---
title: Hexo memo
tags:
  - hexo
  - tips
categories:
  - hexo
date: 2018-02-05 16:33:10
---

[Hexo](https://hexo.io/)使用过程中的备忘录

## Quick Tips
### Hexo生成静态文件
```bash
$ hexo generate
```
或者 简写
```bash
$ hexo g
```

### Hexo 启动服务器
```bash
$ hexo server
```
或者 简写
```bash
$ hexo s
```
启动服务器。默认情况下，访问网址为： http://localhost:4000/

| 参数 | 描述 |
| - | - |
| `-p`, `--port` | 重设端口 |
| `-s`, `--static` | 只用静态文件 |
| `-l`, `--log` | 启动日记记录，使用覆盖记录格式 |
| `--drafts` | 启动预览草稿 |

###Hexo 部署
```bash
$ hexo deploy
```
或者 简写
```bash
$ hexo d
```
部署网站。

| 参数 | 描述 |
| - | - |
| `-g`, `--generate` | 部署之前预先生成静态文件 |