
# Meta.plugin

> 元数据插件模块

## 模块名

> metaModule

## 方法 get()

> 壳子根据前端传的key值，找到tree.json里面对应资源元数据，


### 语法

> metaModule.get(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    key: 'KEY',         // 资源对应key值
}
```

### 参数 callback

```
(event) => {}
```

