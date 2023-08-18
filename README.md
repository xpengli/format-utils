## format-utils-lib

一个封装了 JS 的一些常用方法的工具

## 食用方法
git
1. 下载 npm 包

```shell
npm i format-utils-lib
```

2. 使用 Common 校验函数
```js
import Format  from 'format-utils-lib'
const money =  12341234.246 -> $ 12,341,234.25
Format.formatMoney(money,'$');