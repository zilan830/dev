# 前端开发规范

#### 命名规范

* 项目命名
    - 以```front```开头。
    - 全部采用小写方式，以中划线分隔。
    
    例子：```front-refee-new```

* 目录命名
    - 全部采用小写方式， 以中划线分隔，有复数结构时，要采用复数命名法， 缩写不用复数。

    例子：```assets / styles / components / images / utils / layouts / demo-styles / demo-scripts / doc```

* JS、CSS、SCSS、HTML、PNG 文件命名
    - 全部采用小写方式， 以中划线分隔。
    - 特殊文件可以采用大写。如```App.ts```，```README.md```，```LICENSE```等一些第三方文件。

    例子：```render-dom.js / local-storage.js / index.html / company-logo.png``` 

     
    **特别说明**
    
    **项目```src```内一级文件命名定义为固定名字，不可随意更改，具体如下：**
        
        1、请求地址文件：apis 
        2、静态文件：assets
        3、组件库文件：components
        4、项目定义文件：config
        5、react项目hook文件：hooks
        6、页面文件：pages
        7、路由文件：router
        8、数据管理文件：store
        9、样式文件：styles
        10、通用方法文件：utils

    **文件目录**

        src
        ├─App.tsx
        ├─main.tsx
        ├─utils
        |   ├─base-request.ts
        |   └local-storage.ts
        ├─styles
        |   └index.css
        ├─store
        |   └index.ts
        ├─router
        |   └index.tsx
        ├─pages
        |   └home
        |      ├─index.module.scss
        |      └index.tsx
        ├─hooks
        |   └index.ts
        ├─config
        |   └index.ts
        ├─components
        |   └index.ts
        ├─assets  
        └apis
            └index.ts
**除了```utils```，```assets```之外，其余文件都需要有```index.ts```文件，将本文件所有方法导出，具体导出方式，参照```react-ts-template```中的示例。**
**```pages```文件夹里是页面文件集合，
    






