
# vscode 安装vim插件
# 使用hjkl来控制方向键移动
# 使用i前置编辑  使用a后置编辑 并且进入编辑模式
# 在setting.json编辑使用jj进入编辑模式
```
    "vim.insertModeKeyBindings": [{
        "before": ["j","j"],
        "after": ["<esc>"]
    }]

```

# vim中使用:wq 保存并退出  使用:q!强制退出

``` js
    const aa = 11;
    const bb = 22;
```
``` js
    const aa = 11
    const bb = 22
```

``` js
    const aa = 11
    const bb = 22
```

``` js
    const aa = 1223
    const ba = 234

```

```js
    const userName = "Nowell"
    const age = 100

```

# 选中一个单词然后将其删除
``` vim
    bved
```
### 其中 b 移动到单词的最前方, v 光标选中, e 移动到最末尾 d 表示删除 还有剪切.
### 可以在后面加一个p表示粘贴
