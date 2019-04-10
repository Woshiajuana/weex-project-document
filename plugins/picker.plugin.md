
# Picker.plugin

> 联动插件模块

## 模块名

> pickerModule

## 方法 show()

> 壳子根据前端传的key值，找到tree.json里面对应资源元数据，


### 语法

> pickerModule.show(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    source: 'SOURCE',   // 原始数据
}
```

### 参数 callback

```
(event) => {}
```

