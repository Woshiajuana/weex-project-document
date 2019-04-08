
# Photo.plugin

> 照片插件模块

## 模块名

> photoModule

## 方法 camera()

> 壳子调用相机，拍摄照片返回对应数据。

### 语法

> photoModule.camera(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',                 // app名称
    isTailor: false,            // 是否裁剪
    isCompress: true,           // 是否压缩
}
```

### 参数 callback

```
(event) => {}

event = {
    code: '0000',
    data: 'DATA',
}

DATA = {
    base64: 'BASE64',           // 图片的base64数据
    path: 'PATH',               // 图片的本地路径
}
```

## 方法 album()

> 壳子调用本地相册图库，选取照片返回对应数据。

### 语法

> photoModule.album(options, callback);

### 参数

参数|类型|描述
-------     | -------   |--------
options     |[Object]   | 对象
callback    |[Function] | 回调函数

#### 参数 options

```
{
    app: 'APP',                 // app名称
    isTailor: false,            // 是否裁剪
    isCompress: true,           // 是否压缩
}
```

### 参数 callback

```
(event) => {}

event = {
    code: '0000',
    data: 'DATA',
}

DATA = {
    base64: 'BASE64',           // 图片的base64数据
    path: 'PATH',               // 图片的本地路径
}
```

