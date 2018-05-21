## http-mini
基于Express的小型本地服务器，可用于开发阶段开启本地服务器，跑假数据

## install
```
#全局安装
npm install http-mini -g

#切换到根目录文件夹，例如dist，public等打包后的文件夹
cd dist

#http-mini port
http-mini 8083

#http-mini port n/y
http-mini 8088 n  //n表示不自动打开浏览器窗口

#具体使用示例可以见下面
```

## 示例目录结构 ##

```
dist
├── css
│   └── main.css
├── goform
│   └── index.json
├── js
│   ├── lib
|   |   └── a.js
│   ├── controller
│   │   ├── actions
│   │   │   └── b.js
│   │   |── c.js
│   │   └── d.js
│   └── index.js
└── index.html

#所有的数据文件都存储在goform文件夹下的index.json文件中
#对应一个请求`getOnlineUsers`，在json文件中的存在格式如下

{
    "getOnlineUsers":[
        ...
    ]
}

```
