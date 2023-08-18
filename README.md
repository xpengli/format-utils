## bus-format-utils

一个封装了 JS 的一些常用方法的工具

## 食用方法
git
1. 下载 npm 包

```shell
npm i bus-format-utils
```

2. 使用 Common 校验函数
```js
import Format  from 'bus-format-utils'
const money =  12341234.246 -> $ 12,341,234.25
Format.formatMoney(money,'$');