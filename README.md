# Cookie.js
  这是一个小型的轻量级 Cookie 读写插件，文件小，功能全。
****
## 使用方法
* 创建一个 Cookie , 此方法返回一个 Cookie 对象;
```javascript
Cookies.createCookie(name, value);  //name 和 value 为字符串;
```
* 获取一个 Cookie , 此方法返回制定键名的 Cookie 对象'
```javascript
Cookies.getCookie(name);  //name 为字符串;
```
* 设置 Cookie , 此方法设置一个 Cookie;
```javascript
Cookies.setCookie(cookie);  //Cookie 为一个 Cookie 对象;
```
* 可选的 Cookie 属性;
```javascript
cookie.getName();  //return the cookie's name;

cookie.setName(String);  //set the cookie's name;

cookie.getValue();  //return the cookie's value;

cookie.setValue(String);  //set the cookie's value;

cookie.setExpires(Date);  //set the cookie's deadline, the parameter should be a object of date type;

cookie.setDomain(String);  //set the cookie's domain, the parameter should be a string;

cookie.setPath(String);  //set the cookie's path, the parameter should be a string;

cookie.setSecure(Boolean);  //set the cookie's secure;
```
