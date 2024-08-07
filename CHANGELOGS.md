
# v1.2.0

### 新特性

1. 完整适配了深色模式。

### 优化

1. 对 UI 设计体型进行了调整。

### 修复

1. 修复了 `音乐播放器` `XP 分析工具` 分享链接无法正常获取的问题。

# v1.1.0

云翰工具箱正式在 `Github` 上开源！

### 新特性

1. 添加了 `XP 分析工具`

### 优化

1. 调整了首页文本。
2. 重新设计了菜单的 UI 。
3. 抛弃了 `Vue.js` 的默认图标，改为了 `#.NUT` 图标。

# v1.0.0

恭喜，`云翰工具箱 v1.0.0` 正式发布！

### 新特性

1. 推出了本地版 `云翰工具箱`，支持离线使用。
2. `成就工具` 初步支持了筛选成就。

### 优化

1. 修复了部分页面没有正常变更标题的情况。

# v0.7.1

### 新特性

1. `成就工具` 支持导入 [`UIAF`](https://uigf.org/zh/standards/uiaf.html) 的数据并查询完成状态。

# v0.7.0

### 新特性

1. 添加了 `成就工具` 并且完成了基础的成就查询功能。

# v0.6.1

### 优化

1. 补上了 `音乐播放器` 的更新说明。

# v0.6.0

- 更新时间 : `2024-7-12`

### 新特性

1. 添加了 `音乐播放器` 功能。

## v.0.5.0

- 更新时间 : `2024-6-30 15:32`

### 新特性

1. `翻译器` 新增 `枫丹字体` 。

### 优化

1. 优化了 `翻译器` 的 `软键盘` 再低宽度设备上的显示效果。
2. 优化了 `翻译器` 的 `字体选择器` 。

## v.0.4.4

- 更新时间 : `2024-6-29 22:10`

### 优化

1. `翻译器` 的介绍 Markdown 添加了介绍视频的哔哩哔哩外链播放器。
2. 为后续的布局优化做准备。

## v.0.4.3

- 更新时间 : `2024-6-15 18:02`

### BUG 修复

1. 修复了 `翻译器` 的 `软键盘` 中，普通文字插入错位的问题。

## v.0.4.2

- 更新时间 : `2024-6-15 17:54`

### 新特性

1. `翻译器` 新增 `复制翻译结果` 功能。

### 优化

1. 翻译器
    1. 改进了 `软键盘` 的体验。按键输入和 `Backspace` , `Enter` , `Space` 可以跟随光标位置更新。
    2. UI 布局优化。
2. 可以更方便的浏览更新日志了。

## v.0.4.1

- 更新时间 : `2024-6-15 14:22`

### BUG 修复

1. 修复了 `翻译器` 中，在深色模式下，Markdown 文本颜色显示不正常的问题。

### 新特性

2. 新增 `更新日志` 功能。

### 优化

3. 为 `Markdown 渲染组件` 添加了高度限制选项。
4. Markdown 文件由 `JavaScript + 模板字符串 + import` 的引用方式改为 `Vite 路径的 ?raw 后缀引入`
