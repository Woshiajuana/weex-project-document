
# Resource.plugin

> 资源插件模块

## 模块名

> resourceModule

## 方法 get()

> 获取资源文件路径，壳子需判断对应资源

### 语法

> resourceModule.get(options, callback);

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

