
# Share.plugin

> 分享插件模块

## 模块名

> shareModule

## 方法 to()

> 壳子分享数据到微信、朋友圈等

### 语法

> shareModule.to(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',             // app名称
    title: 'TITLE',         // 标题
    content: 'CONTENT',     // 内容
    linkUrl: 'LINK',        // 链接
    imageUrl: 'IMAGE',      // image地址
    imageBase64: 'IMAGE',   // image的base64数据
}
```

### 参数 callback

```
(event) => {}
```

