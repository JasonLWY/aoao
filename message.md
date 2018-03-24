###需求分析
    1）商品->首页，商品列表，商品详情
    2）购物车-》购物车数量，添加删除商品，购物车提交
    3）订单 ->订单确认（地址管理），订单提交，订单列表，订单详情
    4）支付-》支付
    5）登陆，注册，个人信息，找回密码，修改密码
    
####管理后台
    1）商品管理->添加/编辑商品 查看商品 下架
    2）品类添加-》添加品类，查看品类
    3）订单管理-》订单列表，顶顶干详情，发货
    4）权限->管理员登陆 
####参与
        更深入了解业务和需求
     丰富其他领域的知识
     提防不靠谱的需求
##架构设计和技术选型
    分层架构：优势 松耦合 MVVM
    
###模块化
         AMD CMD  {CommonJS ES6}
         ES6模块化兼容性不好 高版本的浏览器
         主模块=》子模块。。。。。。-》service 数据层-》         
         
            
 ##技术选型
    软件过程{瀑布型。。。。。}
       前后的分离方式 
        构建工具
            框架
                版本控制
                    发布方式
                    
    敏捷开发：循序渐进的方法进行软件开发。满足不断变化的需求。
        
  ##前后端分离
    前后端完全分离
        velocity发布时通断的后到后端
    纯静态的 接口数据交互
        优点：完全脱离后端模板，系统复杂度降低
        缺点：不利与SEO
        优化方案：Server Render/蜘蛛定制页面
                    
  ##框架选型
      脚本：vue jquery react  
      样式框架：css :less sass
      用户端：求稳，用户多样，youSEO要求，多页面应该，
      管理系统：
        求快 用户类型单一，no SEO
   ##构建工具
    webpack 
   ###版本控制 
    git 
   ###发布方式
    发布过程
        拉去待发布的代码
           编译打包
            发布到线上去
     域名分布
        html 
         js+css 
           image 
            域名的请求数目是有限的
           （三个不同的域名去管理不同的资源）                                
           
  ###前后端接口职责
    后端{
        数据存储
        文件服务
         数据接口
    } 
    前端{
        数据请求
        数据处理
        页面展示 
    } 
    -
    接口的文档规范
        模板-----接口名称
            /product/.do-----接口地址
               request------请求信息
               l
               response-----相应信息
               K
               fail
                l  
                
    请求响应
    success//必须需要接口的成功失败的状态标识
    {   
        “status” :0     //接口状态 0 success 1 fail  10 未响应
        "data": {
            "id":1,
            "name":"Jasonlwy"
        }
    }   
    fail
    {
    "status":1`,
    "msg":"该信息错误!!!!"
    }
    
  ##开发环境
    NodeJS
       Git 
        webstorm
            chrome
                Fiddler
                
    nodejs npm 介绍安装
        构建工具webpack 需要
        nodejs 包管理工具npm
        nodeJS官网的安装包
            Mac .pkg
            window .msi
        node -v//查看安装是否成功
        
    Git安装和简介
        git命令行
            git init 
                git  add -A 
                   git commit -m "a"
                   git checkpout branch//切换分支
                    git merge //合并
                      ....  
                git --version //查看安装成功是否
                
            
           
                                          