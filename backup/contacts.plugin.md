
# Contacts.plugin

> 剪切板插件模块

## 模块名

> contactsModule

## 方法 directory()

> 壳子打开电话簿，返回用户选取的一个联系人


### 语法

> contactsModule.directory(options, callback);

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
    data: '用户选取的号码',
}
```

## 方法 call()

> 壳子拨打电话

### 语法

> contactsModule.call(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',         // app名称
    tel: 'TEL',
}
```

### 参数 callback

```
(event) => {}
```

