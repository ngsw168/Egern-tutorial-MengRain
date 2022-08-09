# 前言
本篇是Egern的教学旨在方便大家上手（有帮助的话点个关注吧）

我的TG频道：[点击一键关注](https://t.me/mengyulianmian)

我的TG交流群：[点击一键加入](https://t.me/mengdelaochao)

首先强调本教程是完全免费且公开的，请看完免责声明后进行学习，感谢采用本教学

# 免责声明
MengRain 本仓库中涉及的任何解锁和解密分析脚本仅用于资源共享和学习研究，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。

间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, MengRain 对于由此引起的任何隐私泄漏或其他后果概不负责。

请勿将本仓库内的任何内容用于商业或非法目的，否则后果自负。

如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我将在收到认证文件后删除相关脚本。

MengRain 对任何本仓库中包含的脚本在使用中可能出现的问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害．

您必须在下载后的24小时内从计算机或手机中完全删除以上内容。

任何以任何方式查看此项目的人或直接或间接使用该项目的任何脚本的使用者都应仔细阅读此声明。MengRain 保留随时更改或补充此免责声明的权利。一旦使用并复制了任何本仓库相关脚本或其他内容，则视为您已接受此免责声明。

# 教学开始前的吟唱
本片教学使用的是Egern TF版本【1.4.0（56）】以后更新新的版本我也会对本教学继续更新

Egern俗称小松鼠 是一款新星的网路代理软体，但是上手蛮麻烦目前又不支持外部导入，所以应群友要求我编写了本教程

# 代理的导入
{什么是代理？通俗来说就是你在机场购买的链接}

注意！！！代理的导入提供A B两种选择，请选择其中一种！！！

# A. 订阅链接的导入方法（全部导入，适合机场玩家）：

1.在软体最底部选择[工具]选择[策略组]

![image](https://user-images.githubusercontent.com/89105781/183559957-25aaf76e-71da-4b16-b253-463a82cf9aca.png)

2.点击右上角加号，在类型中选择[External]在URL中填入您的机场订阅链接

![image](https://user-images.githubusercontent.com/89105781/183560335-2df655ff-5443-4124-adda-2fad39bed14f.png)

![image](https://user-images.githubusercontent.com/89105781/183561508-c723ba22-c1ca-4e36-a447-fe3cea570561.png)


PS：更新间隔是指节点的更新频率（比如24小时更新一次）

--------分割线----------------分割线----------------分割线----------------分割线----------------分割线--------

# B. 一条一条的导入方法（适合自建玩家）：

1.在最底下选择工具后打开代理，点击右上角的加号

![image](https://user-images.githubusercontent.com/89105781/183353457-ee3cb598-80ca-4397-86fc-3bee55939dff.png) 

![image](https://user-images.githubusercontent.com/89105781/183353820-098870cf-731a-4d81-829a-49cd234cdb79.png)


2.在内部填入您的订阅链接


![image](https://user-images.githubusercontent.com/89105781/183354301-4d58f776-5360-4a37-8377-190cde494fe2.png)

PS：更具您的机场格式选择在[类型]中选择适合你的订阅类型
（比如：Shadowsocks是对小火箭的兼容则小火箭能用的使用这个格式在Egern就可以使用）
具体表格也放在旁边了

![image](https://user-images.githubusercontent.com/89105781/183358619-32ee1be2-9e6b-4e28-a1c4-5d22d48dffa8.png)
![image](https://user-images.githubusercontent.com/89105781/183354614-a93fca2d-2c89-42e1-8d5a-71331e611c57.png)

# 策略组
{什么是策略组？顾名思义就是所有的策略（节点）的合集，类似于收纳盒}

选择策略组，点击右上角加号，使用一个你喜欢的名字
选择类型（以下是翻译）后选择可用的订阅（比如刚刚你导入的或者直连）（直连是DIECT）PS：建议放入你的所有订阅选路，方便选择

![image](https://user-images.githubusercontent.com/89105781/183359181-8a3cad89-ff27-4ac7-88b5-e26eff58fe82.png)

具体内容 具体内容 具体内容 具体内容 具体内容

![image](https://user-images.githubusercontent.com/89105781/183359325-38c3be40-b049-4e7a-8fe9-3cbc05f5ad3c.png)

# 规则
{什么是规则？即让指定的链接走给他规定的线路如：谷歌走香港，bilibili走中国（直连），TG走最快的代理}

老样子选择右上角的加号添加新的规则
类型的翻译如下：

![image](https://user-images.githubusercontent.com/89105781/183360274-f295a0e2-e650-40f8-b07a-58cfeaa82390.png)

类型的详细解说如下：

此处拿 domain 举例，例如我们要让谷歌走香港节点我们就需要在匹配中填入Google.com；若我们访问的是Googel.HK则无法命中改规则 则走兜底（兜底=Proxy）

此处拿 domain_keywork 举例，例如我们要让谷歌的所有内容走代理，我们只需选择domain_keywork后填入google；具体表现效果是只要链接带google这6个字母就都会走设定的路线

此处那 geoip 举例，例如我们要让中国的链接（此处的中国网页是指结尾是CN的链接）都走直连，那么我们只需使用geoip并在匹配中选择对应的国家代号CN并在策略中选择直连即可

PS A：常用的国家（地区）代号如下：

CN 中国 | US 美国 | TW 台湾省 | HK 香港特别行政区 | MO 澳门特别行政区 | RU 俄罗斯 | US 英国 | JP 日本 | KR 韩国（南韩) | TR 土耳其 |SG 新加坡 | MY 马来西亚

PS B：感谢 @Coldvvater 自愿做的移植工作，这是他的规则仓库：[点击此处跳转](https://github.com/Coldvvater/Egern/tree/master/Rule)　诸位可以在他的仓库中寻找到自己需要的规则


# 重写
{重写是什么？重写是指重写客户端发送的请求，然后再转发给服务器}

普通人用不到不用管他（因为有些模块会自带重写）

【具体怎么自己DIY作者也不会，所以先放概念图吧以后再更新这个板块QwQ】

![image](https://user-images.githubusercontent.com/89105781/183366021-e04891a6-0d2d-42db-bcdd-b4e69e412f61.png)

![image](https://user-images.githubusercontent.com/89105781/183366062-51dfa172-446a-4350-8c5c-e2d4d0ae9930.png)

![image](https://user-images.githubusercontent.com/89105781/183366104-38e121a4-aa69-4b35-a011-820a9b140adf.png)

# 脚本
普通人用不到不用管他（因为有些模块会自带脚本比如BosJS）

# 模块
{什么是模块？模块能作的事情很多例如解锁中国iPhone被锁的功能，比如去广告，比如给YouTube添加机翻字幕等等}

由于是新软件模块都没什么适配XDDDD

在此再次感谢 @Coldvvater 自愿做的移植工作，这是他的规则仓库：[点击此处跳转](https://github.com/Coldvvater/Egern/tree/master/Module)　诸位可以在他的仓库中寻找到自己需要的模块


# 结语
我们十分欢迎各位的补充和纠错，诸位可以加入TG群组进行讨论｛[点击此处跳入吧](https://t.me/mengdelaochao)｝




