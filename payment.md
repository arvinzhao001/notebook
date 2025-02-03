---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://unsplash.com/photos/water-splash-in-close-up-photography-SHE_ZiroE0g
# some information about your slides (markdown enabled)
title: Payment and Account Guide
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
# Introduction of Payment and Account

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>
---
transition: fade-out
---

# 支付过程
支付定义：付款人向收款人转移可被双方接受的债权资产。
支付过程可以划分为三个阶段：交易、清算和结算，这是支撑所有支付行为的核心框架。

- 📝 **交易** - 即用户发起支付、确认身份、生成交易单据等一系列操作
- 🎨 **清算** - 是基于已生成的交易单据进行数据交换、归集以及清分的过程。在此过程中，会完成交易本金和手续费的计算，按照对象汇总生成应收应付金额，并通过支付系统将相关信息发送给清算方
- 🧑‍💻 **结算** - 是根据清分结果完成资金最终实际转移的过程
<br>
<br>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->