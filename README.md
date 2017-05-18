# vue-axios

## 用法

克隆仓库到本地

```
git clone https://github.com/heuuLZP/axios_demo.git
```

进入仓库根目录,安装依赖
```
npm install
```

启动项目
```
npm run dev
```

## 查看效果

自行修改`src/components/Hello.vue`文件中第24行中的如下所示代码。

- 正常请求
  ```
  http.get(api.right, params)
  ```
- 地址不存在
  ```
  http.get(api.error, params)
  ```
- 参数不正确
  ```
  http.get(api.backEnd, params)
  ```

## 项目结构

```
src
├── App.vue
├── assets
│   └── logo.png
├── components
│   └── Hello.vue
├── main.js
├── router
│   └── index.js
└── utils         ## 工具
    └── api.js    ## 封装api
    └── http.js   ## 封装axios
```
