# 更新日志

### 1.5.6 & 2.1.8

`2020-12-29`

**Features**

- plugin: 新增 [mermaid](./plugins/mermaid.md) 插件.
- lang: 新增 [德语](./Internationalization.md#配置文件) 语言包.

### 1.5.5 & 2.1.7

`2020-12-07`

**Features**

- props: 新增 [toolbar-config](./api.md#toolbar-config) 属性.

### 1.5.4 & 2.1.6

`2020-12-04`

**Improvement**

- en-US.js: 优化 en-US 语言包。

### 1.5.3 & 2.1.5

`2020-11-11`

**Improvement**

- upload-images: 优化粘贴 svg 和一些不支持的类型图片时报错的问题。

### 1.5.2 & 2.1.4

`2020-11-05`

**Refactor**

- types: 移除 types 文件夹。

### 1.5.1 & 2.1.3

`2020-11-05`

**Features**

- theme: 新增 [codeHighlightExtensionMap](./senior/code-highlight-extension.md) 配置。

**Improvement**

- github-theme: 样式优化。

### 2.1.2

`2020-10-24`

**Bug Fixes**

- base-editor: 修复 base-editor v-model 失效的问题。

### 2.1.1

`2020-10-21`

**Bug Fixes**

- toolbar menu: 修复 toolbar menu 点击行为失效的问题。

### 1.5.0 & 2.1.0

`2020-10-15`

**Features**

- props: 新增 [codemirror-style-reset](./api.md#codemirror-style-reset) 属性。

**Improvement**

- codemirror-editor: codemirror 由用户自定义配置。

:::danger 重要
为了使开发者更灵活的配置 codemirror 编辑器的相关资源，从该版本开始，codemirror 编辑器将由用户在项目中手动引入[查看详情](./examples/codemirror-editor.md#引入)
:::

### 2.0.1

`2020-10-14`

2.x 版本支持 vue3

### 1.4.11

`2020-10-12`

**Features**

- props: 新增 [default-fullscreen](./api.md#default-fullscreen) 属性。
- lang: 新增 [韩语](./Internationalization.md#配置文件) 语言包。

**Improvement**

- github.css: 优化 github 主题的表格样式。

### 1.4.10

`2020-08-01`

**Bug Fixes**

- copy code plugin: 修复 copy-code-plugin 在预览组件中使用时失效的问题。

### 1.4.9

`2020-07-28`

**Features**

- xss: 支持 xss 规则[扩展](./senior/xss-extend.md)。

### 1.4.8

`2020-07-24`

**Bug Fixes**

- copy code plugin: 修复当编辑器嵌套在 form 标签下使用时，点击复制代码按钮会导致页面刷新的问题。

### 1.4.7

`2020-07-22`

**Features**

- plugin: 新增 [highlight lines](./plugins/highlight-lines.md) 插件.

**Improvement**

- image: 移除插入图片时的默认宽高属性。
- image size: 设置图片宽高的通配符由 { 调整为 {{{。

### 1.4.6

`2020-07-21`

**Bug Fixes**

- lang/zh-CN.js: 修复斜体与无序列表配置缺失的问题。

### 1.4.5

`2020-07-13`

**Bug Fixes**

- copy-code-plugin: 修复在某些场景下复制代码失败的问题.

### 1.4.4

`2020-07-09`

**Bug Fixes**

- upload-image: 修复 上传本地图片 拿不到文件对象的问题。

### 1.4.3

`2020-07-01`

**Bug Fixes**

- xss: 修复 ol 标签 start 属性被 xss 过滤导致某些场景下序号显示不正确的问题。

**Features**

- plugin: 新增 [copy code](./plugins/copy-code.md) 插件。

### 1.4.2

`2020-06-28`

**Improvement**

- 兼容 ie10 和 ie11.

### 1.4.1

`2020-06-21`

**Bug Fixes**

- lang: 修复预览组件使用 vuepress 主题时 tip 插件语言包问题。

### 1.4.0

`2020-06-17`

**Bug Fixes**

- index: 修复从入口文件导出 xss 的值为 undefined 的问题。

**Features**

- 国际化: 支持[国际化](./Internationalization.md)，多语言。

### 1.3.3

`2020-06-11`

**Features**

- editor: 入口文件暴露 xss 实例。

### 1.3.2

`2020-06-09`

**Bug Fixes**

- preview: 修复单独使用 preview 组件时，在图片预览时的图片操作栏的图标缺失问题。

### 1.3.1

`2020-06-06`

**Bug Fixes**

- index.d.ts: 修复使用 ts 编译时报错的问题。
- image preview: 修复图片太大预览时图片溢出的问题。

**Features**

- image upload: 新增粘贴截图触发上传图片的交互。

**Improvement**

- vuepress theme: 优化 vuepress 主题中图片的样式。

### 1.3.0

`2020-05-28`

**Bug Fixes**

- mode: 修复动态切换 mode 属性出现的问题。

**Features**

- toolbar: 新增 preview 工具栏用来开启和关闭预览。
- image-upload: 新增拖放图片上传。
- props: 新增 placeholder autofocus 属性。
- event: 新增 fullscreen-change 事件。
- hotkey: 新增 save 快捷键 CTRL + S。

### 1.2.13

`2020-05-11`

**Features**

- props: mode 属性新增 `edit` 可选值。
- preview: 新增图片预览功能。

**Improvement**

- highlight code: 移除未引用对应代码块语言包时的报错日志。

### 1.2.12

`2020-05-06`

**Bug Fixes**

- xss: 修复 svg 相关标签的属性被过滤的问题。

**Features**

- props: 新增 include-level 属性用来配置生成目录导航时所要包含的标题等级。

:::warning 注意
扩展主题的 api 有细微调整，有使用到的请注意。[查看详情](./theme/github.md)
:::

### 1.2.11

`2020-05-01`

**Improvement**

- license: 新增 MIT 开源协议
- types：新增 d.ts 文件

### 1.2.10

`2020-04-27`

**Bug Fixes**

- anchor：修复标题为中文时锚点失效的问题。

**Improvement**

- anchor：优化锚点生成规则，保证在标题内容相同时锚点的唯一性。

### 1.2.9

`2020-04-27`

**Improvement**

- editor：ul、ol 列表换行时自动插入前缀。

### 1.2.8

`2020-04-25`

**Features**

- hotkeys：新增部分常用功能快捷键。

### 1.2.7

`2020-04-24`

**Features**

- plugin：新增 [代码行号](./plugins/line-number.md) 插件。

### 1.2.6

`2020-04-23`

**Improvement**

- 内部代码优化。

### 1.2.5

`2020-04-22`

**Features**

- toc：支持 [\[toc]] 插入目录。
- toolbar：新增[目录导航](./senior/toc.md)功能。

**Improvement**

- tooltip：增加显示隐藏过渡效果。

### 1.2.4

`2020-04-21`

**Features**

- props：新增 mode 属性。可选值为 `editable`（编辑模式）、`preview`（预览模式）

**Improvement**

- 同步滚动：同步滚动添加平滑效果，增强用户体验

### 1.2.3

`2020-04-20`

**Bug Fixes**

- markdown-line-number-plugin：解决 markdown-it 插件渲染的问题

### 1.2.2

`2020-04-20`

**Features**

- sync-scroll：新增同步滚动

### 1.2.1

`2020-04-19`

**Improvement**

- textarea：undo redo 优化

### 1.2.0

`2020-04-18`

**Bug Fixes**

- insertText: 修复 document.execCommand('insertText') 在 Firefox 上不兼容的问题。

**Features**

- image: 新增 image 可自定义图片大小
- plugin：新增 [katex](./plugins/katex.md) 插件
- plugin：新增 [todo-list](./plugins/todo-list.md) 插件

### 1.1.0

`2020-04-18`

**Features**

- plugin: 新增 [emoji](./plugins/emoji.md) 插件
- props：新增 disabled-menus 属性
- toolbar：新增 [menus](./senior/toolbar.md) 属性

**Improvement**

- tooltip：新增 tooltip 优化交互体验

### 1.0.13

`2020-04-15`

**Bug Fixes**

- theme: 解决使用 cdn 引入时主题失效的问题

**Improvement**

- xss：过滤规则优化
