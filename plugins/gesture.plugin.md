
# Gesture.plugin

> 手势插件模块

## 模块名

> gestureModule

## 方法 set()

> 壳子根据前端传的key值，打开手势设置，


### 语法

> gestureModule.set(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    key: 'KEY',         // 手势对应的key
}
```

### 参数 callback

```
(event) => {}
```

## 方法 check()

> 壳子验证手势，


### 语法

> gestureModule.check(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    key: 'KEY',         // 手势对应的key
}
```

### 参数 callback

```
(event) => {}
```

## 方法 del()

> 壳子删除手势，


### 语法

> gestureModule.del(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    key: 'KEY',         // 手势对应的key
}
```

### 参数 callback

```
(event) => {}
```
