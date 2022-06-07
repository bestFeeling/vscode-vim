




### vim 文本对象

#### 语法: 操作符 + 内外(i,a) + 文本类型
#### 文本类型： w：单词 剩下的被什么包围就使用什么键
#### eg: i"匹配""内的内容   a" 匹配包含"以及"内的内容
#### eg: i{或者i}匹配{}内的内容 a{或者a}匹配包含{}以及{}的内容
#### 特殊 cia 删除函数中的一个参数，并且保留逗号  caa 删除函数中的一个参数并且连同这个函数的逗号  同时进入编辑模式。同理使用dia daa
#### 特殊 cie cae 删除整个文件内容 对于空白行有微小区别
aavm, aac
```js
function getUserName(id, name, age) {
    const age = 20;
    const name = "Nowell"
    const obj = {}
    obj["key1"] = "123"
}
```









