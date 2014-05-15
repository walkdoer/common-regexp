#### COMMON Regular Expression 常用正则表达式

`注明: 代码示例使用语言为javascript`



1. 中文和英文和数字

```js
var regex = /^[\u4e00-\u9fa5\da-zA-Z]+$/
```

2. 双字节字符结构(包括汉字)

```js
var regex = /[^\x00-\xff]*/
```






资源
=====================
1. http://stackoverflow.com/questions/331426/common-regular-expressions
2. http://code.tutsplus.com/tutorials/8-regular-expressions-you-should-know--net-6149
3. [正则匹配中文及常用正则表达式](http://wangwei007.blog.51cto.com/68019/1108694)
