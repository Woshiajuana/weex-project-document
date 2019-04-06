
# Tree

> APP资源文件

## 结构

```
{
    "app": "wow",                                   // app名称
    "entry": "wow_app",                             // app入口资源文件 
    "base": "http://20.0.18.93:32580/dist/BD",      // app资源文件存放服务器url地址
    "version": "0.0.1",                             // app资源文件版本号
    "engine": "0.0.1",                              // 壳子引擎版本号
    "resource": {                                   // 资源文件
        "wow_app": {                                // 一个资源文件对象
            "src": "wow_app.js",                    // 文件名
            "md5": "xxxxxxxxxxxxxxxxxxxxxxxxx",     // 文件的MD5值
            "meta": {                               // 文件需要用到的配置数据
                "arrList": []
            }
        }
    },
    "module": {                                     // app模块插口
        "auth ": {                                  // 模块名
            "tree": "http://20.0.18.93/auth.json"   // 模块的资源文件地址
        }
    }
    "insert": {                                     // 第三方接入APP插口
        "third_party_app": {                        // 第三方APP资源文件地址
            "tree": "http://20.0.18.93/third_party_app.json"
        }
    }
}
```
