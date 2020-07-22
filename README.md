# J3space.Abp.Extensions

[WIP] abp vnext 框架的补充

abp vnext 框架是 C# 平台优秀的开源项目，其模块化的设计，基于 DDD 的清晰的项目结构十分适合二次开发。
 
但是在 startup 项目中仍然有一些不足的地方。

1. 有些项目只在商业版本中可用，例如 Identity Server 模块对客户端，Api 资源的管理等。
2. 默认基于 Bootstrap 和 jQuery 的用户界面，官方提供的替换页面的方法远不如自行设计来的方便。
3. 封装了一些可能不需要的组件，如作为"一等公民"的多租户功能往往并非每个项目都会用到。

为此，本项目主要是基于自己开发过程中的需求，添加一些模块，或者替换原生的一些模块。

- [ ] Identity Server
  - [ ] 客户端资源管理
  - [ ] Api 资源管理
  - [ ] 身份资源管理
  - [ ] Consent 页面
- [ ] Account
  - [ ] 纯 css 的登录、注册界面
  - [ ] 扩展 AccountService 服务
  - [ ] 外部身份认证
