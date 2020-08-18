# Sublime 快捷键  
> - Sublime Text  
> - Sublime Merge  


### 快捷键的修改  
- `ctrl + shift + p`  
- 输入`key bindings`  

快捷键文件的后缀名为`.sublime-keymap`, 其格式为:  
```Json
    { "keys": ["ctrl+shift+alt+f1..12+Num+up/down"], "command": "command_name" },
```

## 快捷键的原理机制  
- 驼峰命名 <-> snake
- sublime_plugin.py 中 Command 类中 name() 方法.

> Mac: /Applications/Sublime Text.app/Contents/MacOS  
> Windows: 安装目录(C:/File Programs/Sublime Test 3/)  

## Sublime Merge 快捷键  

~/Library/Application Support/Sublime Merge/Packages/User/Default.sublime-keymap