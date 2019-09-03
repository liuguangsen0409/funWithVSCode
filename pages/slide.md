title: 玩转 VS Code
speaker: liuguangsen
plugins:

<slide class="bg-black-blue aligncenter" image="https://cn.bing.com/az/hprichbg/rb/RainierDawn_EN-AU3730494945_1920x1080.jpg .dark">

# fun with vscode {.text-shadow}

By liuguangsen {.text-intro.animated.fadeInUp.delay-500}

[:fa-github: Github](https://github.com/liuguangsen/funWithVSCode){.button.ghost.animated.flipInX.delay-1200}

<slide class="bg-trans-dark" :class="size-40 aligncenter" image="http://h1.ioliu.cn/bing/Feringasee_ZH-CN6335425001_1920x1080.jpg .dark">

## 目录

---

* 基本操作 {.text-intro.animated.fadeInUp}
* 快捷键进阶 {.text-intro.animated.fadeInUp.delay-400}
* 文件、符号、代码间跳转 {.text-intro.animated.fadeInUp.delay-800}
* 代码折叠与极速搜索 {.text-intro.animated.fadeInUp.delay-1200}
* 优化编辑器设置 {.text-intro.animated.fadeInUp.delay-1600}
* 调试 {.text-intro.animated.fadeInUp.delay-2s}
* 插件推荐 {.text-intro.animated.fadeInUp.delay-2400}

<slide class="bg-black slide-bottom" image="http://h1.ioliu.cn/bing/DrinkingNectar_ZH-CN6196689688_1920x1080.jpg .light">

:::div {.content-left}
:fa-keyboard-o large:

## 基本操作
#### basic operation

<slide :class="size-60">

## 光标移动

---

::: flexblock {.specs}

#### 1. 单词间的移动

`option + 左 / 右`

---

#### 2. 行首行尾的移动

`command + 左 / 右`

---

#### 3. 代码块间的移动

`command + shift + 左 / 右`

---

#### 4. 全文的移动

`command + 上 / 下`
:::

<slide :class="size-60">

## 文本选择

---

::: flexblock {.specs}

#### 1. 选择单词

`option + shift + 左 / 右`

---

#### 2. 选择当前光标到行首/尾

`command + shift + 左 / 右`

---

#### 3. 选择当前光标到文档首/尾

`command + shift + 上 / 下`
:::

<slide :class="size-60">

## 文本删除

---

::: flexblock {.specs}

#### 1. 删除当前光标前后单词

前 `option + backspace`
后 `option + fn + backspace`

---

#### 2. 删除当前光标前后整行

前 `command + backspace`
后 `command + fn + backspace`

---

#### 3. 删除当前行

`command + shift + k / command + x`
:::

<slide class="bg-black slide-bottom" image="http://h1.ioliu.cn/bing/BicycleRelief_ZH-CN4483533362_1920x1080.jpg .light">

:::div {.content-left}
:fa-terminal large:

## 快捷键进阶
#### shortcut advancement

<slide :class="size-60">

## 快捷键进阶

---

::: flexblock {.specs}

#### 1. 当前光标前后添加行

前 `command + shift + enter`
后 `command + enter`

---

#### 2. 移动当前行代码

`option + 上 / 下`

---

#### 3. 格式化代码

整篇文档 `option + shift + f`
代码段 `command + k command + f`

---

#### 4. 调整缩进

后 `tab`
前 `shift + tab`
:::

<slide :class="size-60">

## 快捷键进阶

---

::: flexblock {.specs}

#### 5. 调换字符位置

`ctrl + t`

---

#### 6. 合并下一行代码

`ctrl + j`

---

#### 7. 返回上一次光标所在的地方

`ctrl + u`

---

#### 8. 多光标

`option + 鼠标左键 / command + d`
:::

<slide :class="size-60">

## 快捷键进阶

---

::: flexblock {.specs}

#### 9. 触发建议

`ctrl + space` 建议改键 (`ctrl + command + space`)

---

#### 10. 参数建议

`command + shift + space`

---

#### 11. 批量重命名

`command + f2`
:::

<slide class="bg-black slide-bottom" image="http://h1.ioliu.cn/bing/CherryLaurelMaze_ZH-CN9887470516_1920x1080.jpg .light">

:::div {.content-left}
:fa-share large:

## 文件、符号、代码间跳转
#### file symbol code jump

<slide :class="size-60">

## 文件间跳转

---

::: flexblock {.specs}

#### 1. 已打开的文件跳转

`ctrl + tab`

----

#### 2. 跳转到指定的文件

`command + p` 搜索文件名

---

#### 3. 跳转到指定文件的指定行

`command + p` 搜索文件名`:`行号
:::

<slide :class="size-60">

## 符号跳转

---

::: flexblock {.specs}

#### 1. 显示当前文件的所有符号

`command + shift + o`
按下`:`可看到符号分类

---

#### 2. 显示已打开文件的符号

`commant + t` 搜索
:::

<slide :class="size-60">

## 引用定义间的跳转

---

::: flexblock {.specs}

#### 1. 跳转到定义

`command + 鼠标左键 / option + f12`

----

#### 2. 跳转到引用

`shift + f12` 建议改建

:::

<slide class="bg-black slide-bottom" image="http://h1.ioliu.cn/bing/MVAU_ZH-CN9430011383_1920x1080.jpg .light">

:::div {.content-left}
:fa-hand-spock-o large:

## 代码折叠与极速搜索
#### code folding and extreme search

<slide :class="size-60">

## 代码折叠

---

::: flexblock {.specs}

#### 1. 折叠展开单个

`command + option + [ / ]`

---

#### 2. 折叠展开当前所有可折叠代码

`command + k, command + 0 / command + k, command + j`

---

#### 3. 自定义折叠

输入 // #region xx // #endregion 只适用于 html js .vue 不行

---

#### 4. 小地图显示色块

设置 editor.minimap.renderCharacters
:::

<slide :class="size-60">

## 极速搜索

::: flexblock {.specs}

#### 1. 单文件搜索

`command + f` 通过 `command + g / command + shift + g` 来查找下一个 / 上一个

---

#### 2. 单文件替换

`command + option + f`

---

#### 3. 多文件搜索

`command + shift + f`

:::

<slide class="bg-black slide-bottom" image="http://h1.ioliu.cn/bing/HardeeCoFair_ZH-CN8647295545_1920x1080.jpg .light">

:::div {.content-left}
:fa-gears large:

## 优化编辑器设置
#### optimize settings

<slide :class="size-60">

## 其他设置

---

::: flexblock {.specs}

#### 1. 让编辑器显示所有的空格，制表符

设置 editor.renderWhitespace\: all

---

#### 2. 缩进参考线

设置 editor.renderIndentGuides

---

#### 3. 行号高亮

设置 editor.renderLineHighlight\: all

:::

<slide :class="size-60">

## 多文件工作区

---

::: flexblock {.specs}

#### 1. 多个编辑器切换

`ctrl + w`

---

#### 2. 一个编辑器切换不同的项目

`ctrl + r`

:::

<slide :class="size-60">

## 终端

---

::: flexblock {.specs}

#### 1. 打开关闭终端

`ctrl + ` `

---

#### 2. 创建新的终端

`ctrl + shift + ` `

---

#### 3. 拆分终端

`command + \`
:::

<slide :class="size-60">

## 工作区

---

::: flexblock {.specs}

#### 1. 创建关闭多个横向编辑器

`command + \ / command + w`

---

#### 2. 横向编辑器切换

`command + 1 / 2 / 3 / ...`

---

#### 3. 专注模式

`command + b command + j`

---

#### 4. 禅模式

`command + k, z`
:::

<slide class="bg-black slide-bottom" image="http://h1.ioliu.cn/bing/Knuthojdsmossen_EN-CA12064544039_1920x1080.jpg .light">

:::div {.content-left}
:fa-bug large:

## 调试
#### debug

<slide :class="size-60">

## 调试前端代码

---

::: flexblock {.specs}

#### 1. 安装插件 Debugger for Chrome

---

#### 2. 打开调试面板 command + shift + d

---

#### 3. 配置 launch.json

---

#### 4. 执行调试
:::

<slide :class="size-60">

## 调试后端代码

---

::: flexblock {.specs}

#### 1. 打开调试面板 command + shift + d

---

#### 2. 配置 launch.json

---

#### 3. 执行调试
:::

<slide :class="size-60">

## launch.json 参数配置

---

```json
{
  // 使用 IntelliSense 了解相关属性。
  // 悬停以查看现有属性的描述。
  // 欲了解更多信息，请访问: https://go.microsoft.com/fwlink/?linkid=830387
  "version": "0.2.0",
  "configurations": [
    {
      "type": "node", // debug 类型
      "request": "launch", // 启动模式 launch 表示由 vscode 启动一个独立的具有 debug 模式的程序 attach 表示附加于一个已经启动的程序（必须已开启 debug 模式）
      "name": "Launch Program", // 配置下拉的值
      "env": {
        "NODE_ENV": "development",
        "PORT": "3888"
      }, // 环境变量
      "program": "${workspaceFolder}/app.js", // 启动 debug 时要运行的可执行文件
      "outFiles": [
        "${workspaceFolder}/**/*.js"
      ] // 用于定位生成的 js 文件 ?
    }
  ],

  // ${workspaceFolder} 工作区文件夹的根路径
  // ${file} 编辑器打开的文件
  // ${env: Name} 环境变量的 Name
}
```

<slide class="bg-black slide-bottom" image="http://h1.ioliu.cn/bing/NightofNights_ZH-CN5872572560_1920x1080.jpg .light">

:::div {.content-left}
:fa-bug large:

## [插件推荐](https://zhuanlan.zhihu.com/p/40417719)
#### extensions recommendation

<slide class="bg-black-blue aligncenter" image="https://cn.bing.com/az/hprichbg/rb/PragueChristmas_EN-AU8649790921_1920x1080.jpg .dark">

## Thanks {.animated.tada}

快使用 [nodeppt](https://github.com/ksky521/nodeppt) 轻松搞定高大上 PPT<br/> nodeppt 助力你的人生逆袭之路！ {.text-into.animated.delay-800.fadeIn}

[:fa-cloud-download: Github](https://github.com/ksky521/nodeppt){.button.animated.delay-1s.fadeInUp}