
# QRCode.plugin

> 元数据插件模块

## 模块名

> qrCodeModule

## 方法 get()

> 壳子根据前端传的key值，找到tree.json里面对应资源元数据，


### 语法

> qrCodeModule.get(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    info: 'INFO',       // 二维码对应信息
    icon: 'ICON',       // 图片url（非必填）
}
```

### 参数 callback

```
(event) => {}

event = {
    code: '0000',
    data: '二维码的BASE64数据'
}
```

