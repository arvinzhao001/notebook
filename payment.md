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
title: 图片和描述
---

# 图片和描述

<div class="flex flex-col items-center">
  <img src="/Users/qiangqiang.zhao/Experiment/slidev/dist/payment/resource/global_account.png" alt="描述图片" class="w-1/2 mt-5"/>
  <p class="mt-5 text-center">这是图片的描述。</p>
</div>