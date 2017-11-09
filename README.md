# AES
AES 加密——javascrpit

#### 示例
```javascript
    //加密
    var str = "我是明文~";
    var pwd = "12345678";
    var estr = String(CryptoJS.AES.encrypt(str,pwd));
    
    
    //解密
    var dstr = CryptoJS.AES.decrypt(estr,pwd).toString(CryptoJS.enc.Utf8);
```
