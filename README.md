
<p align="center">
<img src="https://cdn.tdouplus.com/img/kit-logo.png"  height="200" width="200">
</p>

<p align="center">
<a href="https://github.com/tdouguokit-cre/blob/master/LICENSE">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" title="license-mit" /></a>
<a href="https://ci.appveyor.com/project/gjmvvv/kit">
  <img src="https://ci.appveyor.com/api/projects/status/tk3o571mwbw2rykj?svg=true" title="Build status"/></a>
<a href="https://github.com/tdouguokit/">
  <img src="https://img.shields.io/badge/version-v1-green.svg" title="GitHub version" ></a>
<a href="https://github.com/tdouguokit/releases">
  <img src="https://img.shields.io/badge/Download-1k-green.svg" title="Downloads" /></a>
<a href="https://github.com/tdouguoKit">
  <img src="https://img.shields.io/github/stars/tdouguoKit.svg?style=social&label=Stars" title="GitHub stars" /></a>
<a href="https://github.com/tdouguoKit">
  <img src="https://img.shields.io/github/forks/tdouguoKit.svg?style=social&label=Fork" title="GitHub forks" /></a>
</p>

> We are currently preparing to convert the comments in the code to the English version. We look forward to your joining.

了解 [Core](https://github.com/tdouguokit-core) 源码


Kit for Unity 是Unity3D开发的工具包集合, 集成常见的开发组件以免于重复造轮子。

Kit 设计初衷则是根据业务需求自由组合搭配其中组件, 项目在任何阶段都可以轻松接入。

由多个部分组成Kit, 例: 基础组件、业务服务等。

- 任意基础组件都可抽取到其他项目中使用
- 业务服务基于基础组件扩展(业务服务+依赖基础组件)即可抽取到其他项目中使用.


## 关于 Kit[尚未出生,孵化中. . . ]

Kit 是Unity3D开发的工具包集合, 集成常见的开发组件,工具,组件库等. 免于重复造轮子
,Kit设计初衷则是根据业务需求自由组合搭配其中组件\tool\dll等,项目在任何阶段都可以轻松接入。


## 主要特色

***kit-core (.net)***

- base
	- 静态工具(时间戳转换,字符串优化,IO相关操作)
	- 事件消息
	- 引用池
- 自定义池
- 线程池


***kit-unity***

- [ ] 新手引导(NoviceGuide)
- [ ] (Timeline)新手引导编辑器
- [ ] (Timeline)剧情编辑器
- [ ] 任务编辑器
- [ ] 技能编辑器
- [ ] 动画编辑器
- [ ] 特效编辑器
- [ ] 2D地图编辑器
	- 根据刷的方块或其他自动生成1个物理碰撞或安装指定规则生成大的碰撞
	- 刷地图版块功能
- [ ] ***Setting*** 实现本地数据缓存, key=value
- [ ] ***Network*** 实现网络连接 tcp,udp,kcp
	- [ ] socket-tcp 功能:断线重连、心跳检测、粘包、拆包 扩展协议 protobuf
	- [ ] scoket-udp
	- [ ] socket-kcp
	- [ ] net-htpp Get、Post请求, 提供自定义请求头,RES非对称加密 等技术处理
- [ ] ***FSM*** 有限状态机
- [ ] ***Download*** 实现并发下载,多线程下载 
- [ ] ***Res*** 集成 Resources,StreamingAssets-AB,网络下载AB,管理资源, 基于XAsset实现 AssetBundle,自定义开发AssetBundleEditor指定打包规则.
	- [ ] ***Scene*** 基于Res(编辑器、AB),实现场景之间切换,附加,移除.
	- [ ] ***Audio*** 基于Res(编辑器、AB),网络动态下载,网络在线资源(mp3,wav)等
	- [ ] ***Picture*** 基于Res(编辑器、AB),实现Sprite自动化引用管理以及释放,网络动态下载,网络在线资源
	- [ ] ***Entity*** 基于Res(编辑器、AB),实现GameObject 对象池处理资源加载卸载
- [ ] ***pool*** 对象池
- [ ] ***Video*** 视频
- [ ] ***Data***
	1. data-table 二维表结构(excle,sqlite)
	2. data-node 节点结构(xml,json)
- [ ] ***Event*** 提供模块之间消息通讯, 以及异步线程之间通讯
- [ ] 内嵌Web浏览器(BuiltInWeb)
- [ ] 热更新(xLua\IRuntime)
- [ ] ***Utility*** 工具 
	1. [依赖Unity] 截屏、GPS定位、IO处理、音频转换(AudioClip)、Windows对话框、Misc(WWW请求、图片、UI、Input)等
	2. 时间戳、 数据处理、Misc(string相关处理)等
- [ ] ***i18n*** 国际化
- [ ] ***Process*** 流程 控制游戏/App整体流程


***kit-tool***

- unity 自动打包
	- [ ] android@{apk} 
	- [ ] ios@{xcode project,ipa}
	- [ ] android@{apk} ios@{ipa] 自动上传 fir.im
	- [ ] ios@{ipa} 自动上传appstore


## 学习 Kit

[文档](https://kit.tdouplus.com) 

或者您也可以通过 issues 来提出您的问题，我们及时为您解答。

请不要提问「现成」问题，即那些简单搜一搜就能得到答案的，对经验和洞察力几乎没有要求的问题。 

详请参考《[提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md)》


## 授权

开源许可：[MIT license](https://opensource.org/licenses/MIT).


## 项目开发计划

进入 [Kit开发计划](https://www.teambition.com/project/5c641818c156ca00170bcc98/tasks/scrum/5c6418a49502f00017416bd7)来了解未来的开发序列。


## 技术支持

- E-mail: me@tdouplus.com
- slack: kit.slack (敬请期待)
<!-- QQ群: 633542313 [![](https://pub.idqqimg.com/wpa/images/group.png)](//shang.qq.com/wpa/qunwpa?idkey=1235068de91ee5b340182dfa324f2d118fa586c8dd4053946763172de0f5d580) -->
<!-- > QQ群禁止水聊，但对技术类提问范围不限制，如：遇到友情链接中的项目的问题也可以直接在群中`@相关作者`。 -->


## 友情链接

### 热更新方案

- [ILRuntime](https://github.com/Ourpalm/ILRuntime) 项目为基于C#的平台（例如Unity）提供了一个纯C#实现的，快速、方便并且可靠的IL运行时，使得能够在不支持JIT的硬件环境（如iOS）能够实现代码的热更新（`@蓝色幻想`）

- [XLua](https://github.com/Tencent/xLua) 为Unity、 .Net、 Mono等C#环境增加Lua脚本编程的能力，借助xLua，这些Lua代码可以方便的和C#相互调用。（`@John`）


### 优秀的开源框架/项目

- [QFramework](https://github.com/liangxiegame/QFramework) QFramework 是一套 渐进式 的 快速开发 框架。目标是作为无框架经验的公司、独立开发者、以及 Unity3D 初学者们的 第一套框架。框架内部积累了多个项目的在各个技术方向的解决方案。学习成本低，接入成本低，重构成本低，二次开发成本低，文档内容丰富(提供使用方式以及原理、开发文档)。

- [XAssets](https://github.com/xasset/xasset) xasset 提供了一种使用资源路径的简单的方式来加载资源，简化了Unity项目资源打包，更新，加载，和回收的作业流程。 ([fjy](https://github.com/fengjiyuan))

- [GameFramework](http://gameframework.cn/) 是一个基于 Unity 5.3+ 引擎的游戏框架，主要对游戏开发过程中常用模块进行了封装，很大程度地规范开发过程、加快开发速度并保证产品质量。（[@Ellan](https://github.com/EllanJiang)）

- [ET框架](https://github.com/egametang/ET) 是一个Unity3d客户端+C#分布式服务端框架。使用组件式开发，提供客户端热更，服务端热更功能，提供erlang式分布式消息机制（[@熊猫](https://github.com/egametang)）

- [CatLib](https://catlib.io) 是一套渐进式的服务提供者框架。框架为客户端提供多个实现，并把他们从多个实现中解耦出来。服务提供者的改变对它们的客户端是透明的，这样提供了更好的可扩展性。她不仅易于上手，还便于与第三方库或既有项目整合。([@喵喵](https://github.com/yb199478)) 

- [BlackFire](https://github.com/BlackFire-Studio/BlackFire) Framework 是专门为了提高中小型企业程序研发团队工作效率和降低中小型企业研发成本而设计的Unity3D游戏开发框架，框架遵循MIT协议，目前还在开发阶段，预计未来框架将友好地面向游戏、三维仿真、VR、AR、Web、区块链等业务开发团队。 ([@Alan](https://github.com/0x69h)) 
