# Clash 订阅转换模板


项目施工中！尚不完善

本项目为 [Custom_OpenClash_Rules](https://github.com/Aethersailor/Custom_OpenClash_Rules) 项目的衍生项目，目的在其他 Clash 软件中实现相近的使用体验。

本项目所有规则文件由上游规则文件自动生成，均不存在 DNS 泄露。

目前测试阶段，尚不完善

- 全分组模板  

  规则全面，由上游项目规则自动生成，添加了依赖 GeoSite 和 GeoIP 的国内直连分流规则，适合在性能强劲无续航需求（如 PC）等设备上使用
  
  
- Lite 轻量化模板  
  
  由全分组版精简而来，只包含基本的分流规则内容，属于国内白名单，实现简单的国内直连功能，适合单节点用户使用
  
  
- Mobile 移动端模板  
  
  由全分组版精简而来，去除了移动端用不到的一些规则（如游戏平台、国内媒体）等规则
