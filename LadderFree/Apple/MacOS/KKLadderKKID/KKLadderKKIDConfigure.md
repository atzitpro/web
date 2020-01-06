###### 金刚梯>金刚帮助>金刚1.0金刚号梯>
### 配置说明
#### 适用于 苹果电脑MacOS

#### 特色
  - [ 一拖九 ](https://github.com/a2zitpro/web/blob/master/onefornine.md)：一号在手，全家自由
  - [ 万能号 ](https://github.com/a2zitpro/web/blob/master/multipurposekkid.md)：一号万能，多机通用
 
#### 配置说明
在苹果电脑上配置金刚与在苹果手机上配置类似，关键是下面几点：

类型：<font color="Red"> IPSec上的L2TP </font>
选择：通过VPN连接发送所有流量

参数分散在多个屏幕上

1、进入 设置>网络，点击创建一个新服务：

苹果计算机配置屏幕1<br>
- 接口：选VPN<br>
- 类型：选<font color="Red"> IPSec上的L2TP </font><br>
- 在 服务器名称 处填入<font color="Red"> AAA金刚 </font><br>
- 点击 创建<br>



     
2、下一窗口填 服务器地址 和 账户名称：

苹果计算机配置屏幕2
- 在 服务器地址 处填入：<font color="Red"> atz开头的串 </font>
- 在 账户名称 处填入：<font color="Green"> 金刚号 </font>
- 点击 鉴定设置，弹窗：


苹果计算机配置屏幕3
- 在 密码 处填入：<font color="Green"> 金刚密码 </font>
- 在 共享密钥 处填入：<font color="Red"> mft </font>
- 点击 好、确认 关闭窗口
- 在前一窗口点击右下角的 高级，选择 通过VPN连接发送所有流量

3、点击 好 回到上一窗口，点 连接，开始连接金刚。

4、状态显示已连接，屏幕顶部网路图标处 开始计时，则表示 金刚连接成功，即可自由上网。

- 如果连接失败，则请参阅[ 《金刚L2型报错信息、原因及处置》](https://github.com/a2zitpro/web/blob/master/errormessageofL2.md)



    



#### 推荐阅读
- [金刚梯](https://github.com/a2zitpro/web/blob/master/dlb.md)
- [金刚帮助](https://github.com/a2zitpro/web/blob/master/list_elpkkvpn.md)
- [金刚公司类](https://github.com/a2zitpro/web/blob/master/list_a2zitpro.md)
- [金刚产品与服务](https://github.com/a2zitpro/web/blob/master/list_kkproducts&services.md)
- [金刚1.0金刚号梯](https://github.com/a2zitpro/web/blob/master/list_helpkkvpn1.0.md)
- [金刚号梯产品获取与配置](https://github.com/a2zitpro/web/blob/master/list_kkproducts1.0.md)

