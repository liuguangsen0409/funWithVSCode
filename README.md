# funWithVSCode

极客时间玩转vscode笔记

## install

```
npm install -g nodeppt
```

## usage

* new: 使用线上模板创建一个新的 md 文件
* serve: 启动一个 md 文件的 webpack dev server
* build: 编译产出一个 md 文件

```
# create a new slide with an official template
$ nodeppt new slide.md

# create a new slide straight from a github template
$ nodeppt new slide.md -t username/repo

# start local sever show slide
$ nodeppt serve slide.md

# to build a slide
$ nodeppt build slide.md
```

## keyboard shortcuts

* Page: ↑/↓/←/→ Space Home End
* Fullscreen: F
* Overview: -/+
* Speaker Note: N
* Grid Background: Enter
