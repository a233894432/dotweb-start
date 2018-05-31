# DotWeb-Start
基于dotweb的示范项目结构

## 注意事项
* 使用配置文件方式，包含app.conf、dotweb.conf、dotlog.conf
* bin目录为特定目录，建议在开发环境时，将编译生成的文件输出到该目录
* 确保bin目录下conf/develop目录下3个配置文件存在


## 目录说明
* config：全局配置文件定义及使用代码
* const：全局常量
* core：全局核心对象
* document：文档目录
* global：全局访问对象定义及入口
* protected：业务逻辑处理模块，包含数据模型、数据操作等
* resources：开发\测试\生产不同环境资源、配置文件及版本信息
* server：web服务目录，包含常规处理逻辑、路由、静态资源等
* task：task服务目录，主要负责调度器相关
* util：通用方法

## 依赖项
* github.com/devfeel/dotweb
* github.com/devfeel/dotlog
* github.com/devfeel/mapper
* github.com/devfeel/middleware
* github.com/devfeel/database