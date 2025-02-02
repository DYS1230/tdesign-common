---
title: Transfer 穿梭框
description: 以直观的方式在两栏中移动选项元素，是对选项进行单个或批量移动从而完成挑选的数据容器。左栏是“源”，右边是“目标”。
isComponent: true
usage: { title: 'Live Demo', description: '' }
spline: form
---

### 基础穿梭框

包含穿梭框最基础的功能和组合元素。需要两框之间的元素迁移时，便于元素的选择。

{{ base }}

### 带搜索框的穿梭框

基础穿梭框上支持搜索功能，当穿梭框中数据量较大时，提供给用户更快捷的数据项定位能力。

{{ search }}

### 带分页的穿梭框

针对数据量较多的场景，可以通过 `pagination` 将选项分页展示。

{{ pagination }}

### 支持自定义标题、底部、操作按钮及数据渲染

穿梭框的标题、底部、操作按钮和数据渲染都可以自定义渲染。

{{ custom }}

### 空数据的穿梭框

当数据为空时会展示暂无数据，也可以根据需求配置空数据展示。

{{ empty }}

### 与 Tree 结合使用

还支持配合 `Tree` 组件使用。适用于复杂选项的场景。

{{ tree }}
