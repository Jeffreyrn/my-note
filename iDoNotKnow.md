## console

- [console debug](https://elevenbeans.github.io/2018/03/10/10-Tips-for-JS-Debugging-with-Console/)

- console.dir() Displays an interactive list of the properties of the specified JavaScript object

## defer vs async

- [彻底搞懂 defer & async](https://segmentfault.com/a/1190000013480391)
- [async vs defer attributes](http://www.growingwiththeweb.com/2014/02/async-vs-defer-attributes.html)


## GET vs POST

GET后退按钮/刷新无害，POST数据会被重新提交
GET对数据长度有限制，当发送数据时，GET 方法向 URL 添加数据；
URL 的长度是受限制的（URL 的最大长度是 2048 个字符）。POST无限制。
与 POST 相比，GET 的安全性较差，因为所发送的数据是 URL 的一部分。
在发送密码或其他敏感信息时绝不要使用 GET ！POST 比 GET 更安全，
因为参数不会被保存在浏览器历史或 web 服务器日志中。

## 加法运算符

在加法的过程中，首先把等号左右两边进行了求原值ToPrimitive()操作，然后如果两个原值只要有一个是String类型，就把两个原值都进行转化字符串ToString()操作，进行字符串拼接；否则把两个原值都进行转化数字ToNumber()操作，进行数字相加

## 变量的存储方式

栈：自动分配内存空间，系统自动释放，里面存放的是基本类型的值和引用类型的地址

堆：动态分配的内存，大小不定，也不会自动释放。里面存放引用类型的值。

基本类型是值传递 引用类型是址传递

## split

参数支持正则表达式

## js trim
The trim() method removes whitespace from both ends of a string