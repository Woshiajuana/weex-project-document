
# Http.plugin

> 资源插件模块

## 模块名

> httpModule

## 方法 get()

> 壳子接口GET请求

### 语法

> httpModule.get(url, data, options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
url         |[String]   | 请求接口
data        |[Object]   | 请求对象
options     |[Object]   | 配置参数
callback    |[Function] | 回调函数

#### 参数 options

```

url = 'http://api.app.com/login'

data = {
    phone: '13188888888',
    passowrd: '123456'
}

options = {
    timeOut: 60 * 1000,   // 超时时间设置
}
```

#### 参数 callback

```
(event) => {}

event = {
    code: '0000',
    data: '接口返回的数据'
}
```

## 方法 post()

> 壳子接口post请求

### 语法

> httpModule.post(url, data, options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
url         |[String]   | 请求接口
data        |[Object]   | 请求对象
options     |[Object]   | 配置参数
callback    |[Function] | 回调函数

#### 参数 options

```

url = 'http://api.app.com/login'

data = {
    phone: '13188888888',
    passowrd: '123456'
}

options = {
    timeOut: 60 * 1000,   // 超时时间设置
}
```

#### 参数 callback

```
(event) => {}

event = {
    code: '0000',
    data: '接口返回的数据'
}
```

