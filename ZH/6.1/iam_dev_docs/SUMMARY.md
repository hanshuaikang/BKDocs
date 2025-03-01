# Summary

## 权限中心接入
* [快速指引]()
    * [接入指引](HowTo/Guide.md)
    * [接入流程图](HowTo/GuideFlow.md)
    * [错误码](HowTo/FAQ/ErrorCode.md)
    * [FAQ](HowTo/FAQ/FAQ.md)
    * [问题排查指引](HowTo/FAQ/Guide.md)
* [QuickStart]()
    * [简介](QuickStart/01-Begin.md)
    * [准备工作](QuickStart/02-Prepare.md)
    * [模型注册](QuickStart/03-Model.md)
    * [鉴权](QuickStart/04-Auth.md)
    * [无权限申请](QuickStart/05-Application.md)
    * [了解更多](QuickStart/06-More.md)
* [HowTo]()
    * [接入样例]()
        * [样例 1: 无关联实例权限](HowTo/Examples/01-ActionWithoutResource.md)
        * [样例 2: 关联简单实例权限](HowTo/Examples/02-ActionWithResource.md)
        * [样例 3: 使用拓扑层级管理权限](HowTo/Examples/03-Topology.md)
        * [样例 4: 使用属性管理权限](HowTo/Examples/04-Attribute.md)
        * [样例 5: 配置操作组优化权限申请](HowTo/Examples/05-ActionGroup.md)
        * [样例 6: 配置常用操作优化权限申请](HowTo/Examples/06-CommonActions.md)
        * [样例 7: 配置依赖操作优化权限申请](HowTo/Examples/07-RelatedActions.md)
        * [样例 8: 系统间调用无权限申请](HowTo/Examples/08-NoPermissionApply.md)
        * [开源项目: 接入权限中心的实现](HowTo/Examples/10-OpenSource.md)
    * [相关方案]()
        * [无权限交互方案](HowTo/NoPermissionApply.md)
        * [权限模型自动初始化及更新 migration](HowTo/Migrateion.md)
        * [依赖操作权限方案](HowTo/RelatedActions.md)
        * [新建关联权限方案](HowTo/ResourceCreatorAction.md)
        * [大规模实例级权限限制](HowTo/LargeScaleInstances.md)
        * [依赖环境属性方案](HowTo/RelatedEnvironments.md)
    * [问题排查]()
        * [错误码](HowTo/FAQ/ErrorCode.md)
        * [FAQ](HowTo/FAQ/FAQ.md)
        * [问题排查]()
            * [问题排查指引](HowTo/FAQ/Guide.md)
            * [开发接入问题](HowTo/FAQ/Debug/Develop.md)
            * [SaaS 报错](HowTo/FAQ/Debug/SaaS-DebugTraceAPI.md)
            * [SaaS: 组织架构同步异常](HowTo/FAQ/Debug/SaaS-DeptSync.md)
            * [SaaS: 回调第三方系统失败](HowTo/FAQ/Debug/SaaS-Callback.md)
            * [鉴权接口 debug](HowTo/FAQ/Debug/PolicyAPIDebug.md)
            * [运维问题](HowTo/FAQ/Debug/Deployment.md)
            * [IAM-Debug CLI](HowTo/FAQ/Debug/DebugCLI.md)
    * [部署运维]()
        * [部署及运维说明](HowTo/OPS/Deploy.md)
        * [升级部署说明](HowTo/OPS/Upgrade.md)
        * [开发测试环境搭建](HowTo/OPS/Develop.md)
* [Explanation]()
    * [说明: 实例视图](Explanation/01-InstanceSelection.md)
    * [说明: 权限模型](Explanation/02-AuthModel.md)
* [Reference]()
    * [规范及说明]()
        * [系统注册名词规范](Reference/NamingRules.md)
        * [AppCode 和 SystemID 说明](Reference/AppcodeAndSystemID.md)
        * [资源的拓扑说明](Reference/ResourceTopology.md)
        * [性能测试说明](Reference/Benchmark.md)
    * [API 文档]()
        * [概览]()
            * [后台 API 和 ESB API 说明](Reference/API/01-Overview/01-BackendAPIvsESBAPI.md)
            * [接口协议前置说明](Reference/API/01-Overview/02-APIBasicInfo.md)
            * [系统间接口鉴权](Reference/API/01-Overview/03-APIAuth.md)
        * [模型注册]()
            * [模型注册 API](Reference/API/02-Model/00-API.md)
            * [名词及概念](Reference/API/02-Model/00-Concepts.md)
            * [系统 System](Reference/API/02-Model/10-System.md)
            * [资源类型 ResourceType](Reference/API/02-Model/11-ResourceType.md)
            * [实例视图 InstanceSelection](Reference/API/02-Model/12-InstanceSelection.md)
            * [操作 Action](Reference/API/02-Model/13-Action.md)
            * [操作组 ActionGroup](Reference/API/02-Model/14-ActionGroup.md)
            * [通用查询 Common Query](Reference/API/02-Model/15-CommonQuery.md)
            * [系统 token 查询](Reference/API/02-Model/16-Token.md)
            * [常用操作配置 CommonActions](Reference/API/02-Model/17-CommonActions.md)
            * [功能开关配置 FeatureShieldRules](Reference/API/02-Model/18-FeatureShieldRules.md)
            * [新建关联配置 ResourceCreatorAction](Reference/API/02-Model/19-ResourceCreatorAction.md)
        * [资源反向拉取]()
            * [名词及概念说明](Reference/API/03-Callback/00-Concepts.md)
            * [资源拉取 API](Reference/API/03-Callback/01-API.md)
            * [1. list_attr](Reference/API/03-Callback/10-list_attr.md)
            * [2. list_attr_value](Reference/API/03-Callback/11-list_attr_value.md)
            * [3. list_instance](Reference/API/03-Callback/12-list_instance.md)
            * [4. fetch_instance_info](Reference/API/03-Callback/13-fetch_instance_info.md)
            * [5. list_instance_by_policy](Reference/API/03-Callback/14-list_instance_by_policy.md)
            * [6. search_instance](Reference/API/03-Callback/15-search_instance.md)
        * [鉴权]()
            * [SDK 鉴权](Reference/API/04-Auth/01-SDK.md)
            * [直接鉴权](Reference/API/04-Auth/02-DirectAPI.md)
        * [无权限申请]()
            * [生成无权限申请 URL](Reference/API/05-Application/01-GenerateURL.md)
            * [第三方鉴权失败返回权限申请数据协议](Reference/API/05-Application/02-NoPermissionData.md)
        * [授权及回收]()
            * [资源拓扑授权/回收](Reference/API/06-GrantRevoke/01-Topology.md)
            * [批量资源拓扑授权/回收](Reference/API/06-GrantRevoke/02-BatchTopology.md)
        * [新建关联]()
            * [新建关联属性授权接口](Reference/API/07-ResourceCreatorAction/01-Attribute.md)
        * [查询类]()
            * [说明](Reference/API/08-Query/README.md)
            * [policy get 获取某条策略详情](Reference/API/08-Query/01-PolicyGet.md)
            * [policy list 拉取系统下某个操作的策略列表](Reference/API/08-Query/02-PolicyList.md)
            * [policy subjects 根据策略 ID 拉群策略对应的用户信息](Reference/API/08-Query/03-PolicySubjects.md)
    * [SDK]()
        * [Python SDK](Reference/SDK/01-PythonSDK.md)
        * [Go SDK](Reference/SDK/02-GoSDK.md)
        * [Java SDK](Reference/SDK/03-JavaSDK.md)
        * [SDK 测试用例](Reference/SDK/04-SDKTestCase.md)
    * [表达式]()
        * [表达式定义](Reference/Expression/01-Schema.md)
        * [表达式求值](Reference/Expression/02-Eval.md)
        * [表达式解析](Reference/Expression/03-Translate.md)
    * [其他]()
        * [性能测试说明](Reference/Benchmark.md)
