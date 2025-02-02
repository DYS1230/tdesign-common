---
title: Layout 布局
description: 用于组织网页的框架结构。
isComponent: true
usage: { title: 'Live Demo', description: '' }
spline: layout
---

### 基础用法

`<Layout>`：layout 容器、可包裹子组件`<Header>`、`<Footer>`、`<Aside>`、`<Content>`。

当子元素中包含 `<Aside>` 时，全部子元素会水平排列，否则会垂直排列。

{{ base }}

### 侧边导航布局

主要包含侧边导航、内容区域。该布局下，页面间切换的操作效率较高，但压缩了内容区域的横向空间。适用于导航层级较深，导航效率要求较高的页面。

{{ aside }}

### 顶部导航布局

主要包含顶部区域、内容区域。该布局下，横向空间的展示效率很高，但损失了导航空间，降低了页面导航的切换效率。适用于主要操作区域在内容区域，对页面叠好效率要求不高的页面。对于该类页面，为了保证信息布局的稳定性，内容区域的宽度常设置为固定宽度。

{{ top }}

### 组合导航布局

主要包含顶部导航、侧边导航、内容区域。顶部导航和侧边导航的组合使用，提升了导航效率。多用于信息架构复杂、对导航效率有一定要求的应用型网站。

{{ combine }}
