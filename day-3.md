### Vim的操作符
  需要在vim.operatorPendingModeKeyBindings中配置按住操作符以后得配置
#### d 删除 

this a very long words

使用 ```d + L```删除到结尾
使用 ```d + H```删除到开头 
以上操作仍处于非编辑模式，如果需要到编辑模式可以是  ```c + L``` 或者 ```c + H```


### 今日操作符

d: 删除
c: 删除并且进入编辑模式
y: 复制 注意使用y的复制是使用p粘贴 而不是`Ctrl + v`

### 今日移动操作

e -> end 移动到单词结尾
b -> before 移动到单词之前


``` js
function gunName(string) {

}
```
### 组合
在单词中间可以使用```bce```删除当前单词
如果在单词开头可以直接使用```ce```

``` js
function funName() {

}
```

