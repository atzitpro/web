###### 玩转金刚>金刚字典>
###### 玩转金刚>金刚字典 精简版>
###  梯、梯子、云梯 是如何帮您突破墙的封锁的？
以下表述基于该假定：您来自且身处独裁专制国家<br>

- <strong>代理型云梯</strong>
  - 什么是<strong> 代理型云梯</strong>
    - 所谓<strong> 代理型云梯</strong>，亦称<strong> 跳板型云梯</strong>，由前端、后台两部分构成
    - 前端是一套软件，安装在用户的设备（手机、Windows等）上
    - 后台由若干台部署在境外的、充当跳板的虚拟服务器及部署于其上的后台软件构成
  - <strong>跳板型云梯 </strong>的工作原理
    - 因[ google.com](https://www.google.com/)、[YouTube.com ](https://m.youtube.com/)等早已被<strong> GFW </strong>所墙——即被<strong> GFW </strong>列入黑名单，故墙内用户无法直接访问它们
    - 当墙内用户启动安装在自己设备上的<strong> 跳板型云梯 </strong>的前端软件时，该前端软件穿透GFW自动搜寻到安装在<strong> 跳板服务器 </strong>上的后端软件，在前后端软件之间的相互认证完成后开始通讯
    - 前端软件之所以能够穿透<strong> GFW </strong> ，重要原因是<strong> 跳板服务器 </strong>的IP地址不在<strong> GFW </strong>的黑名单里
    - 截止此刻，一条从用户设备到<strong> 跳板服务器 </strong>、再从<strong> 跳板服务器 </strong>到目标网站之间的通讯管道已经建立
    - 用户从自己的设备上发出访问被墙网站的请求
    - 该请求不再直接发往目标网站，而是发往<strong> 跳板服务器 </strong>上的后台软件
    - 再由<strong> 跳板服务器 </strong>上的后台软件转达给目标网站
    - 用户所需的信息从被墙的目标网站沿原路反方向流回用户的设备，从而实现访问境外网站的目的
    - 简而言之，<strong>跳板型云梯 </strong>的工作原理是改用户直接访问目标网站为用户经由跳板服务器间接访问目标网站
  - <strong>跳板型云梯 </strong>的变种
    - 从源代码是否开放的维度划分，<strong>跳板型云梯 </strong>可分为
      - 开源<strong> 跳板型云梯 </strong>
      - 闭源<strong> 跳板型云梯 </strong>
  - <strong>跳板型云梯 </strong>及其变种存在的短板、重大缺陷
      - 容易被<strong> GFW </strong>捕捉到其行踪，从而导致服务中断，用户无法使用
        - 导致其<strong> 跳板服务器 </strong>被<strong> GFW </strong>所墙
        - 通讯被<strong> GFW </strong>强行切断、毒化、异步、延时过长等
      - 安全程度低，导致其用户中的异见人士频频被捕
        - 对用户的个人信息、隐私、上网痕迹等，在技术、制度、法律层面保护程度太低、或保护完全缺失
      - 因开源导致产品的前端、后台分别由不同公司或人群研发、运营、管理，导致前端、后台处于松耦合状态，给<strong> GFW </strong>和骇客以可趁之机
         - 后台跳板服务器+后台软件被称为<strong> 机场</strong>
         - 负责运营、管理后台的公司或群体被称为<strong> 机场主</strong>
      - <strong>机场主</strong>跑路，致用户上当受骗
        - 据来自市场的反馈，少数无良<strong> 机场主 </strong>以极低的年价向墙内用户兜售其不限流量、高网速、高品质的线路与节点——即后台服务，等网罗到一定数量用户、总营收达到一定数额时，立即关张卷钱跑路，令贪图便宜的用户所付年费打水漂，然后<strong> 机场主 </strong>再换一张面孔继续行骗。在金刚看来，<strong>机场主 </strong>之所以选择跑路、行骗，是因为他所收取的低廉年费根本无法覆盖其成本，赢利则更无望。因此，跑路和行骗将是必由之路
      - 容易被墙
        - 因<strong> GFW </strong>与</strong> 机场 </strong>之间捉与被捉的猫鼠游戏频繁发生，导致<strong> 跳板服务器 </strong>频繁被墙，其帮墙内用户翻墙的效果将大打折扣，用户体验很差
      - 被墙时恢复服务耗时太长
        - 当<strong> 跳板服务器 </strong>被墙、用户无法访问<strong> 跳板服务器</strong>、翻墙失败时，<strong> 机场 </strong>应具备自动、快速感知被墙的能力，且应有能力迅速向用户提供全新的、确保尚未被墙的<strong>跳板服务器</strong>，用户才能继续翻墙
        - 但来自市场的报告证实：大量<strong> 机场 </strong> 因为没有自动、快速侦测、感知<strong> 跳板服务器 </strong>被墙、迅速提供新的<strong> 跳板服务器 </strong>替代被墙服务器、迅速恢复服务的能力，故在<strong> 跳板服务器 </strong>被墙时，恢复服务所需时间过长，严重影响用户体验


   - 原因至少有：
     - 前端与后台之间的通讯缺少加密或加密级别不够高、被<strong> GFW </strong>嗅探成功并破解
     - 流量特征未做伪装，或伪装失败，被<strong> GFW </strong>识破
     - 通讯协议、加密协议选择失当
     - 开源致其产品的技术秘密完全暴露，使<strong> GFW </strong>和骇客容易破解

- VPN型云梯


#### 返回到
- [玩转金刚梯](https://github.com/a2zitpro/web/blob/master/LadderFree/A.md)
- [金刚字典](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/KKDictionary.md)
- [金刚字典 精简版](https://github.com/a2zitpro/web/blob/master/LadderFree/kkDictionary/KKDictionaryShortVersion.md)



