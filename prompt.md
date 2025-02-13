---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://unsplash.com/photos/water-splash-in-close-up-photography-SHE_ZiroE0g
# some information about your slides (markdown enabled)
title: 常用Prompt积累
info: |
  ## Slidev Starter Template
  Introduction of Payment and Account.
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---
# 日常LLM Prompt积累

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>
---
layout: image-right
image: https://cover.sli.dev
---

# 资损分析

分析指定函数调用链路资金风险

```ts
我是一名技术人员，你作为技术专家，帮我分析一下这个函数调用链路潜在的资金损失，请使用Plantuml描述这个函数的调用时序图。要求如下：
1、需要分析所有分支逻辑和路径，分析所有直接调用或者间接调用的函数，不要有遗漏。
2、使用note重点展示金额字段相关逻辑，包括金额字段的来源、使用、加工和存储，还有依赖的状态、类型等条件
3、时序图展示逻辑要和代码逻辑顺序保持一致。使用 “==“对逻辑块进行总结。
4、只有碰到以下情况时才建立participant：入口函数、http接口请求、grpc接口请求、保存DB。入口函数显示在时序图左侧。
```
<!-- Footer -->

[Learn more](https://sli.dev/features/line-highlighting)

<!-- Inline style -->
<style>
.footnotes-sep {
  @apply mt-5 opacity-10;
}
.footnotes {
  @apply text-sm opacity-75;
}
.footnote-backref {
  display: none;
}
</style>