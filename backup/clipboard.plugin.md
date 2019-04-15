
# Clipboard.plugin

> 剪切板插件模块

## 模块名

> clipboardModule

## 方法 copy()

> 壳子复制文案到剪贴板


### 语法

> clipboardModule.copy(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    text: 'TEXT',       // 文案
}
```

### 参数 callback

```
(event) => {}
```

## 方法 paste()

> 壳子粘贴文案

### 语法

> clipboardModule.paste(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
}
```

### 参数 callback

```
(event) => {}

event = {
    code: '0000',
    data: '文案'
}
```

