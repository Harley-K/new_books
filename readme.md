## 开发步骤
- 写接口,SOLID 开发原则  
- 实现接口 service 可被注入 @可被注入  
- 起名字
    容器.绑定<interface类>(名字).to(具体的类)  
    容器 : 单利/重新构建  
    container.bind<Warrior>(TYPES.Warrior).to(Ninja);  
- 执行注入到需要的类型

## 说明


        . 基于 SOLID 的 inversify 框架完成 IOC 的 Nodejs 小架构
        ├── app.ts 项目入口文件
        ├── constant 常亮定义
        ├── controllers 路由文件
        ├── interface 接口文件
        ├── ioc 控制中心
        ├── modules 数据模型
        ├── node_modules 依赖文件
        ├── package-lock.json 包🔐文件
        ├── package.json 包管理
        ├── readme.md 说明
        ├── services 服务层实现接口
        ├── tsconfig.json ts 配置文件
        ├── yarn-error.log yarn 报错
        └── yarn.lock 包🔐文件


# TIP
记住when 的名字和 event 的名字一定要对应上!!!

仔细看文档!