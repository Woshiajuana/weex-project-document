
# Resource.plugin

> 资源插件模块

## 模块名

> resourceModule

## 方法 get()

> 第一步壳子根据前端传的key值，找到tree.json里面对应资源数据的value js资源文件名，
> 第二步判断该js资源文件是否已经下载到本地，如果未下载结合tree.json的base值，
> 去服务器下载对应的js资源到本地，然后将本地文件路径返回给前端；
> 如果已经下载就直接将本地文件路径返回给前端。

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

```
(event) => {}
```

