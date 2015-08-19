# topLine
使用apicloud模仿《今日头条》，数据存储使用平台mcm

部署到自己的应用中，首先你必须.

1. 将modelClass导入到你的Database中. 
2. 将fs、weibo模块添加到你的应用中. 
3. 将widget包文件->的config文件中的id配置为你自己的应用ID. 
4. 将widget包文件->的config文件中的weibo配置为你自己应用的对应key等信息. 

                topLine/<br />
                ├── classJson/
                │   ├── article.json        文章数据   
                │   ├── channel.json               频道数据
                │   ├── comment.json               评论数据
                │   ├── file.json                  图片数据
                │   ├── interest.json              兴趣爱好数据
                │   └── modelClass.json            class表结构
                └── widget                      项目源码包
