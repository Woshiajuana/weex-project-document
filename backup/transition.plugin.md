
# Transition.plugin

> 过渡弹窗模块

## 模块名

> transitionModule

## 方法 show()

> 壳子弹窗页面，


### 语法

> transitionModule.show(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    url: 'URL',         // 资源对应key值
    animated: 'true',   // 是否有动画
}
```

### 参数 callback

```
(event) => {}
```

## 方法 hide()

> 壳子隐藏弹窗页面，


### 语法

> transitionModule.hide(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    animated: 'true',   // 是否有动画
}
```

### 参数 callback

```
(event) => {}
```
