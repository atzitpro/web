###### 玩转金刚梯 免梯阅读版>
#### 苹果电脑MacOS >
### 《金刚号梯配置说明》

#### 特色
  - [ 一拖九 ](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/OneForNine.md)：一梯在手，全家自由
  - [ 万能梯 ](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/KKLadderKKIDMultipurpose.md)：一梯万能，多机通用
 
#### 配置说明
- 在苹果电脑上配置金刚号梯与在苹果手机上配置类似
- 关键是以下几点：

- 类型：IPSec上的L2TP
- 选择：通过VPN连接发送所有流量

- 参数分散在多个屏幕上

- 1、进入 设置>网络，点击 创建一个新服务：

- 苹果计算机配置屏幕1<br>
  - 接口：选VPN<br>
  - 类型：选 IPSec上的L2TP
  - 在 服务器名称 处填入<font color="Red"> AAA金刚 </font><br>
  - 点击 创建<br>



     
- 2、下一窗口填 服务器地址 和 账户名称：

- 苹果计算机配置屏幕2
  - 在 服务器地址 处填入：<font color="Red"> atz开头的串 </font>
  - 在 账户名称 处填入：<font color="Green"> 金刚号 </font>
  - 点击 鉴定设置，弹窗：


- 苹果计算机配置屏幕3
  - 在 密码 处填入：<font color="Green"> 金刚密码 </font>
  - 在 共享密钥 处填入：<font color="Red"> mft </font>
  - 点击 好、确认 关闭窗口
  - 在前一窗口点击右下角的 高级，选择 通过VPN连接发送所有流量

- 3、点击 好 回到上一窗口，点 连接，开始连接金刚。

- 4、状态显示已连接，屏幕顶部网路图标处 开始计时，则表示 金刚连接成功，即可自由上网。

- 如果连接失败，则请参阅[ 《金刚号梯报错、原因、对策》](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/KKLadderKKIDErroMessage.md)


#### 返回到
- [玩转金刚梯](https://github.com/a2zitpro/web/blob/master/LadderFree/A.md)
