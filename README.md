# vue3-snippets-for-vscode

这是一个适配 Vue3 Api 的 snippets 插件

**新增特性: 支持快速 console.log，方便调试**
**注意** :本插件可能不完全适用于 vue2

## 大概这样用

<img src="https://cdn.jsdelivr.net/gh/wejectchen/vue3-snippets-for-vscode@master/assets/guide.gif?raw=true" style="zoom: 40%;" />

# 特性

目前支持的代码片段

### 模版片段

|  关键词  |                                代码片段                                 |
| :------: | :---------------------------------------------------------------------: |
|  vinit   | `<template></template><script setup lang="ts"></script><style></style>` |
| template |                   `<template><div></div></template>`                    |
| scripte  |                   `<script setup lang="ts"></script>`                   |
|  style   |                        `<style lang=""></style>`                        |
|   css    |                        `<style scoped></style>`                         |
|   scss   |                      `<style lang="scss"></style>`                      |
|   Sass   |                      `<style lang="sass"></style>`                      |
|   Less   |                      `<style lang="less"></style>`                      |

### script&vue 片段

|      关键词      |                   代码片段                   |
| :--------------: | :------------------------------------------: |
|      Import      |          `import {...} from '...'`           |
|       Data       |            `data(){return {...}}`            |
|      Setup       |          `setup(){...return{...}}`           |
|      vText       |                `v-text="..."`                |
|      vHtml       |                `v-html="..."`                |
|      vShow       |                `v-show="..."`                |
|       vIf        |                 `v-if="..."`                 |
|      velse       |                   `v-else`                   |
|     velseif      |              `v-else-if="..."`               |
|       vFor       |       `v-for="... in ..." :key="..."`        |
| vFor(withoutKey) |             `v-for="... in ..."`             |
|       vOn        |                 `v-on="..."`                 |
|      vBind       |                `v-bind="..."`                |
|      vModel      |               `v-model="..."`                |
|      vSlot       |                `v-slot="..."`                |
|      vOnce       |                   `v-once`                   |
|   iscomponent    |     `<component :is="..."></component>`      |
|    **vprops**    | `const props = defineProps({ foo: String })` |
|    **vemits**    |  `const emit = defineEmits(['...', '...'])`  |

### vue-router 片段

|      关键词      |                        代码片段                        |
| :--------------: | :----------------------------------------------------: |
|    beforeeach    |      `router.beforeEach((to, from, next) =>{...}`      |
|  beforeresolve   |    `router.beforeResolve((to, from, next) => {...}`    |
|    afterEach     |         `router.afterEach((to, from) => {...}`         |
|   beforeenter    |          `beforeEnter(to, from, next) {...}`           |
| beforeRouteEnter |        `beforeRouteEnter(to, from, next) {...}`        |
| beforeRouteLeave |        `beforeRouteLeave(to, from, next) {...}`        |
|      vroute      | `{'path':...,name:...,component: () => import('...')}` |

**Enjoy!**
