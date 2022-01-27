# vue3-snippets-for-vscode

这是一个适配 Vue3 Api 的 snippets 插件

**注意** :本插件可能不能完全不适用于 vue2

## 大概这样用

<img src="https://raw.githubusercontent.com/wejectchen/vue3-snippets-for-vscode/master/assets/guide.gif" style="zoom: 40%;" />

# 特性

目前支持的代码片段

### 模版片段

|  Prefix  |                            Snippets content                             |
| :------: | :---------------------------------------------------------------------: |
|   vue3   | `<template></template><script setup lang="ts"></script><style></style>` |
| template |                   `<template><div></div></template>`                    |
| scripte  |                   `<script setup lang="ts"></script>`                   |
|  style   |                        `<style lang=""></style>`                        |
|   css    |                        `<style scoped></style>`                         |
|   scss   |                      `<style lang="scss"></style>`                      |
|   Sass   |                      `<style lang="sass"></style>`                      |
|   Less   |                      `<style lang="less"></style>`                      |

### script&vue 片段

|      Prefix      |                Snippets content                |
| :--------------: | :--------------------------------------------: |
|      Import      |           `import {...} from '...'`            |
|       Data       |             `data(){return {...}}`             |
|      Setup       |           `setup(){...return{...}}`            |
|      vText       |                 `v-text="..."`                 |
|      vHtml       |                 `v-html="..."`                 |
|      vShow       |                 `v-show="..."`                 |
|       vIf        |                  `v-if="..."`                  |
|      velse       |                    `v-else`                    |
|     velseif      |               `v-else-if="..."`                |
|       vFor       |        `v-for="... in ..."  :key="..."`        |
| vFor(withoutKey) |              `v-for="... in ..."`              |
|       vOn        |                  `v-on="..."`                  |
|      vBind       |                 `v-bind="..."`                 |
|      vModel      |                `v-model="..."`                 |
|      vSlot       |                 `v-slot="..."`                 |
|      vOnce       |                    `v-once`                    |
|   iscomponent    |      `<component :is="..."></component>`       |
|    **vprops**    | `const props = defineProps({   foo: String })` |
|    **vemits**    |   `const emit = defineEmits(['...', '...'])`   |

**Enjoy!**
