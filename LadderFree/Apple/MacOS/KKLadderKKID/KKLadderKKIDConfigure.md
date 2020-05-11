###### 玩转金刚梯 免梯阅读版>
#### 苹果电脑MacOS >
### 《金刚号梯配置说明》

#### 特色
  - [ 一拖九 ](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/OneForNine.md)：一梯在手，全家自由
  - [ 万能梯 ](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/KKLadderKKIDMultipurpose.md)：一梯万能，多机通用
 
#### 配置
- 预备知识和工作
  - 在开始以下操作之前，请首先阅读[《配置注意事项》](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/ConsiderationsWhileConfigureKKID.md)
  - 请准备金刚号及配套参数以备用
    - 请在《派号通知单》邮件中取出金刚号、金刚密码、服务器地址、预共享密钥以备用
    - 如果您已经能翻墙出来，请在 官网>菜单>我的金刚 下，点击金刚号，在 配置信息 项下，取出金刚号、金刚密码、服务器地址、预共享密钥以备用
  - 在苹果电脑上配置金刚号梯与在苹果手机上配置类似，关键是：
    - 类型：IPSec上的L2TP
    - 选择：通过VPN连接发送所有流量
  - 参数分散在多个屏幕上

- 点击 设置>网络，再点 创建一个新服务：
![image](https://github.com/a2zitpro/web/blob/master/LadderFree/Apple/MacOS/KKLadderKKID/217915F1-5B28-49AE-9A0F-E7ECCC1C6EBB.png)
  - 接口：选VPN
  - 类型：选 IPSec上的L2TP
  - 服务名称：填入 AAA金刚 或 金刚号
  - 点击 创建
- 下一窗口填 服务器地址 和 账户名称：
![image](https://github.com/a2zitpro/web/blob/master/LadderFree/Apple/MacOS/KKLadderKKID/559239BC-39C0-4940-89B0-3E5FE837F055.png)
  - 在 服务器地址 处填入：atz开头的串 
  - 在 账户名称 处填入：金刚号
- 点击 鉴定设置，弹窗：
![image](https://github.com/a2zitpro/web/blob/master/LadderFree/Apple/MacOS/KKLadderKKID/macos-screen3.png)
  - 在 密码 处填入：金刚密码
  - 在 共享密钥 处填入：mft
  - 点击 好、确认 关闭窗口
- 点击 好 回到上一窗口
- 点 高级，弹窗：
![image](https://github.com/a2zitpro/web/blob/master/LadderFree/Apple/MacOS/KKLadderKKID/A6F969F0-F85B-4E2D-8CDB-5B5E895DCD38.jpeg)
  - 照上图勾选
- 点 连接，开始连接金刚
- 当状态显示已连接、屏幕顶部网路图标处 开始计时，则表示 金刚连接成功，即可自由上网
- 如果连接失败，则请参阅[ 《金刚号梯报错、原因、对策》](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/KKLadderKKIDErroMessage.md)


#### 返回到
- [玩转金刚梯](https://github.com/a2zitpro/web/blob/master/LadderFree/A.md)
- [金刚字典](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/KKDictionary.md)
