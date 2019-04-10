
# Location.plugin

> GPS定位插件模块

## 模块名

> locationModule

## 方法 get()

> 壳子获取用户的位置信息，


### 语法

> locationModule.get(options, callback);

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

data = {
    code: '0000',
    data: '位置信息',
}
```

