
#### 安装依赖

```console
npm install
```

#### 开发实时编译

```console
npm run dev
```

#### 开发者工具导入项目

使用`微信开发者工具`新建项目，本地开发选择项目dist目录(需要先执行生成dist目录)，会自动导入项目配置。


#### 目录结构

├── src
    ├── components                         //组件
    ├── ├──card-detail 
    ├── ├──htmlParser
    │   └──loading                     
    ├── pages                               //页面
    │   ├── card-detail                     //详情
    │   └── index                           //首页
    ├── wxParse       
    ├── app.wpy                             //入口文件
    ├── .gitignore                          //git忽略文件
    ├── .wepyignore                         //wepy忽略文件
    ├── package.json                        //包配置文件
    ├── project.config.json                 //项目配置文件
    └── wepy.config.js                      //wepy配置文件



