# wxdecoder-微信开放平台加密数据解密组件

特点
---

- 纯JS单文件
- 无其他第三方库依赖
- 方便集成到小程序

使用方法：
---

添加wxdecoder.js到小程序项目即可

代码示例：
---
```javascript
// Obtain the WXDecoder constructor
var WXDecoder = require('./wxdecoder.js')

// Instante a WXDecoder
var wxDecoder = new WXDecoder(appId, sessionKey);

// Decode the data
var data = wxDecoder.decode(iv, encryptedData);
```

许可
---
基于[**ricmoo/aes-js**](https://github.com/ricmoo/aes-js)修改完成，特此感谢。

WTH is this?
---
This project is useful for Chinese developers only far now. So there is no more introduction in English. Special thanks for [**ricmoo/aes-js**](https://github.com/ricmoo/aes-js) : )
