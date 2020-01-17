###### 玩转金刚梯>金刚字典>
### VPN与代理服务器的区别
- 长城防火墙GFW的基本使命
  - 您身在墙内，想访问Google、YouTube等网站
  - 但长城防火墙GFW不希望您成功访问它们
  - 所以GFW把这些网站放入其黑名单
  - 当您访问任何网站时，先得过GFW这一关
  - 当GFW发现您要访问的网站已在其黑名单中时，即命令浏览器报告404错：网页找不到
- 代理服务器的工作原理是
  - 请不要直接访问Google、Youtube等
  - 而是访问部署在墙外的代理服务器
  - 当代理服务器未被GFW发现、未被放入黑名单时，总可成功访问代理服务器
  - 然后再经由代理服务器访问Google、Youtube等，因此，代理服务器被称为“跳板”
  - 当代理服务器被GFW发现且放入黑名单后，代理服务器失灵
  - 因此，提供代理服务器的商家必须有一种能力一一感知某一台代理服务器是否被GFW放入了黑名单
  - 一但感知到被放入黑名单，则立即废掉该台代理服务器再向用户提供另一台确信未被长城防火墙GFW放入黑名单的代理服务器
  - 代理服务器釆用以上工作原理可为墙内用户提供翻墙服务
  - 代理服务器被俗称为“机场”
  - 采用代理方式的著名翻墙软件有SS/SSR(Shadowsocks、ShadowsocksR)
- VPN


#### 返回到
- [玩转金刚梯](https://github.com/a2zitpro/web/blob/master/LadderFree/A.md)
- [金刚字典](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/KKDictionary.md)
