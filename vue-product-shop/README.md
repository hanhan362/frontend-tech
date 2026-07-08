# Vue 商品图文选购页面

## 功能演示

一个基于 Vue 3 的商品展示与选购单页面应用。

### 使用的 Vue 指令

| 指令 | 用途 |
|---|---|
| `v-for` | 循环渲染 6 个商品卡片，`:key` 绑定商品 id |
| `v-bind:src` | 动态渲染商品图片 |
| `v-bind:style` | 评分 ≥ 4 红色边框，否则灰色 |
| `v-bind:disabled` | 库存为 0 时禁用购买按钮 |
| `v-model` | 评分滑块、购买数量输入框、底部单选框 |
| `v-on:click` | 点赞、数量加减、购买弹窗 |
| `v-if` | 弹窗显示/隐藏、售罄标记 |
| `computed` | 选中商品信息、订单合计金额 |

### 使用方法

直接用浏览器打开 `product-shop.html` 即可运行，无需安装任何依赖。

### 文件结构

```
vue-product-shop/
└── product-shop.html    ← 完整页面（HTML + CSS + Vue 3）
```
