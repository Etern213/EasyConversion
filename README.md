# EasyConversion

## 更新日志
```
版本1.0.8： 修复了一个括号匹配的小bug
版本1.0.7： 修复63楼提出的松和鬆问题；修复67楼提出的物品链接问题(2023-03-09)
版本1.0.5： 使用了一个更精准，CPU占用更低的方式实现，感谢彩虹UI作者的启发。大概率是最后一个版本了(2023-03-01)
版本1.0.4： 改了改逻辑，让插件只翻译聊天中的发言部分(说、大喊、副本、小队、频道)等等，不再翻译系统文字部分，解决1.0.3残留问题。同时解决了32楼提出的么、麽和麼对应问题。(2023-03-01)
版本1.0.3： 修复18楼提出的两个问题，但是还是存在一些角色名被翻译的情况，比如系统文字提示某某某获得了成就(2023-03-01)
```
## 一、介绍

插件实现了聊天系统的简繁转换，包括接受信息和发送信息两部分。

插件具体会实现以下两个功能
1、将接受到的信息内繁体内容转换为简体显示在聊天栏内，让你更容易看懂。
2、将你发送的信息转化为繁体发送出去，省去来回切换简繁输入法的麻烦。现在用简体打字发出去自动是繁体
(注意，是发出去别人看起来变为繁体，你自己看起来依旧是简体，因为你自己发送的繁体文字也受到了插件过滤变为了简体)

插件借鉴了爱不易作者07年发的某个帖子的思路，感谢作者[https://ngabbs.com/read.php?tid=1114270]


## 二、注意事项(请在下载前仔细阅读以下部分)

#### 1、插件只包括聊天系统的简繁转换
插件只包括聊天系统的简繁转换，其他界面文字不会受影响。
特例：聊天泡泡不会受影响，该是简体还是简体，该是繁体还是繁体。

#### 2、插件只提供简易的简繁转换功能
插件只提供简易的简繁转换功能，一些本地化翻译的差异不会被翻译。
比如，亚服的"致命一擊"只会被翻译成"致命一击"，不会被翻译成"暴击"。
同样的，你发出去的"暴击"也只会被插件修饰成"暴擊"，不会被翻译成"致命一擊"。
一些副本名称的差异也是一样。

#### 3、出现报错、词库不全欢迎反馈

#### 4、新做了一个简体转繁体的版本给台湾玩家使用，后缀添加了-TraditionalVersion用以区分


## 三、插件下载
见右侧release


## 四、NGA帖子链接
https://ngabbs.com/read.php?&tid=35528965
