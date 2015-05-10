Android下的优秀开发库数不胜数，在本文中，我列举的多是开发流程中最常用的一些。如果你还想了解更多的Android开源库，可以查看我的GitHub Star，过滤Java选项，每一个库都是我认真查看或者编译运行的，希望对你产生帮助。

一、兼容类库

ActionBarSherlock : Action Bar是Android 3.0后才开始支持的，ActionBarSherlock是让Action Bar功能支持2.X后的所有平台，而且他会自动的判断是调用原生Action Bar还是使用扩展ActionBar。在我的小熊词典里有用到这个库，而且很多非常知名的App也在使用这个库。GitHub Official ActionBar科普 最新消息（2013年7月）：Android官方发布的的Support Library Revision 18 开始支持ActionBar的兼容。所以可以不用再使用ActionBarSherlock了。
Android-ViewPagerIndicator : 这是与ViewPager兼容的一个分页指示器库。分页指示器（Friends 和 Suggested就是分页，而下面蓝色的小条就是指示器，ViewPagerIndicator支持多种样式的指示器。）：GitHub
NineOldAndroids  : NineOldAndroids 将 Honeycomb (Android 3.0) 的动画 API 扩展到了Android 1.0以上。这个库的作者即是ActionBarSherlock的作者，也是Android-ViewPagerIndicator的作者，Jake Wharton， 非常厉害的一个人，Github关注量超过1.6K，如果你也做Android开发或者即将开始学习Android开发，一定要去Follow他，而且留意一下他每次的star和follow信息，经常会有很惊奇的发现。Jake Wharton
HoloEverywhere：在Android 4.0时，Google引入了新的主题风格—Holo，多数厂商都想统一界面设计UI，因此更加具有兼容性的Holo主题库HoloEveryWhere便成为很多开发者的选择。在Android的官方Blog中也对HoloEveryWhere这个库有所推荐，点此查看官方博客对HoloEveryWhere的介绍。HoloEveryWhere的Github。
Android-Datepicker: 兼容Android 4.0的datepicker至Android 2.2。 GitHub
二、扩展功能库

SlidingMenu : SlidingMenu 能非常容易的让开发者实现程序的抽屉效果，所谓的抽屉效果如下图所示，通常被用作呼出菜单。而且SlidingMenu能很方便的与ActionBarSherlock融合，在官方GitHub上有关于如何融合的说明。 GitHub  同时，想要达到相同功能也可以看另一个Drawer设计：Android-Undergarment
滑动效果演示
AppMsg : 优雅的弹出类似Toast的消息提示，支持3种状态Alert,Confirm以及Info。GitHub
Drag-Sort-ListView : 很多人都用过在一个ListView中通过拖拽对已有的数据进行排序操作。Drag-Sort-Listview就是实现这一功能的开源库。GitHub
Android-Flip : 轻松实现类似FlipBoard的翻页功能。 GitHub
Android-PullToRefresh : Android下拉刷新组件。 GitHub    此外，该作者还有另外一个实用度和关注量极高的项目–另一种Android ActionBar的实现：GitHub  另：GitHub上另一个Android-PullToRefresh的实现。GitHub

ActionBar-PullToRefresh： 基于ActionBar的下拉刷新组件，在下拉的时候会替换掉ActionBar，显示更新中… GitHub Demo下载
picasso:  程序中经常面临加载网络图片的情况，成熟做法：异步下载->缓存->显示，Picasso一行代码就可这三步轻松完成。GitHub GitHubPage ，GitHub上图片异步加载缓存类库很多，你也可尝试使用Android-Universal-Image-Loader 或者 LazyList 后面将介绍到的afinal(国人项目)也具有此功能。
Card-UI: Google很早之前开始在自家的App内使用卡片式布局，CardUI极其美观大方，想要在自己的App中集成卡片UI布局，那么就轻松地用这个项目吧。GitHub 或者你也可以使用这个库来完成卡片布局。CardLib 另一个卡片式布局: GitHub
Android-DragArea：Android拖拽排序，拖拽移动 库。GitHub (Opera Android浏览器的拖拽排序就是用的这个库)
Android-StaggeredGrid: Android 下类pinterest布局。GitHub

Android 类 Pinterest 布局

FlipImageView: 通过扩展ImageView，实现了ImageView的各种翻转效果。GitHub 体验地址
aChartEngine: Android绘制K线图，以及各种丰富功能的图表。Official Site average_temperature
SmoothProgressBar：平滑的ProgressBar，各种效果。GitHub 体验地址

各式各样的ProgressBar

SuperToasts: 一个愤青对Toast的超强扩展，支持Toast中显示Progressbar，显示图片，显示文等等效果，快去感受下吧！Play GitHub

AndroidFloatLabel：Android Textview 浮动提示，效果是类似下图的。GitHub

浮动提示

cropper:Android截图和旋转库，轻松实现头像和一些场景下的图片操作。GitHub

Android Cropper

StickyGridHeaders:给GridView加上Header。GitHub

GridHeader

avatar-android: 一个用来展示头像的库，支持多种展示方式（圆形，方形）。GitHub 下载感受
Background-ViewPage:支持背景图同时滑动的ViewPager。感受地址 GitHub
pinned-section-listview: 类似Google联系人里的分类列表效果，通过关键字设置不同的分类。GitHub 感受地址
DraggablePanel：实现类似Youtube的拖拽缩小，滑动删除效果。GitHub 另一个 原文地址 查看效果图（图片较大）
Progress-Button: 支持Progress-bar的Button。GitHub 体验地址
GoogleStyle-Datatime-Picker：做的很精致的Google风格的时间选择器。 Play GitHub
Caldroid：另一个很棒的Android-Calendar。GitHubCaldroid
有一个很棒的Date Time Number Picker。 GitHub
Android-CircleButton：Android圆形按钮。 GitHub
FreeFlow: 支持多种展示方式的布局方法。GitHub
AsymmetricGridView： 另一个类似FreeFlow的很酷的布局库。GitHub Apk DemoAsymmetricGridView
JazzViewPager：提供多种ViewPager的过场动画。 GitHub
Photo-Process：Android下给照片加各种滤镜。GitHub  Apk Demo

Android-UndoBar: 类似Google Gmail中的Undo bar实现。GitHub 另一个
ScrollBarPanelWithClock：类Path侧边滚动条时钟效果。 感受地址
activity-animation:一个库，收集Activity animation 动画 GitHub Apk体验
shake-detector: android晃动检测。GitHub
parallaxlistview：这种视差效果最早是由Path引入的，优美的效果一下抓住了用户的眼球，无聊的时候就会拽啊拽的，Android下也有一个仿Path的第三方库： GitHub Apk体验Path
poppyview: 提供类似Google Plus和Chrome上的下滑浮出View效果。GitHub APK体验地址
android-circlebutton
  三、工具类库：

  首先，就我个人开发经验，总结一下平常用到的一些最常用的功能：

必不可少的调试功能
下载，比如图片，文件。
将下载的文件进行解压。
请求服务器，比如说上传登陆信息，更新某些数据，又或者上传头像文件。
从文件系统中选择要操作的文件（图片，拍照，视频，拍摄视频）。
有时候也需要爬取某些网页数据。
存储一些配置信息
播放视频
再有一个特殊需求就是关乎Android程序UI设计，图标是个很麻烦的问题。每次都难以找到合适的Android 设计UI。
随后，我将很有针对性的推荐一些功能库，来简化上面的问题。

DebugLog：更加机智的调试功能，能够友好的显示调试信息所在类和函数。GitHub
afinal： afinal是一个很方便的工具库。GitHub  作者博客（注：国人项目哟）
一行代码就可以对数据库进行增删改查。 
完全注解方式就可以进行UI绑定和事件绑定。无需findViewById和setClickListener等。
轻松实现Android上传文件，POST数据，下载文件（支持断点续传，随时停止下载任务 或者 开始任务）。
一行代码加载网络图片。
android-async-http: Android下的异步HTTP库。GitHub   文档  PS：作者的GitHub值得关注。
发送异步http请求，并且可在回调函数中处理返回响应Response。
http请求在thread线程，不会阻塞UI线程。
请求使用线程池（ThreadPool）实现，优化了并发的资源使用。
支持Multipart 文件上传。
如果Request请求失败，会自动请求。
支持Json解码。
支持存储Cookies到Preference中。
支持gzip处理Request以及Response。
整个库只有19KB。
http-requests: Java http请求库，设计的很优雅的一个库，推荐。 GitHub
async-http-client: Android下的异步 Http 和 WebSocket 库。  GitHub
支持代理设置
支持分片儿处理请求返回内容
支持WebSocket
zt-zip: 压缩和解压库。 GitHub
压缩和解压
单独操作文件压缩和解压。
替换zip文件中的某个文件
jarchivelib: 另一个zip的压缩解压库。 GitHub
aFileChooser：文件选择器,用于选择需要操作的文件 GitHub
image-chooser-library: 图片和视频的选择库。 GitHub Demo
jsoup: HTML解析，并且能很好理解DOM，CSS，以及JQuery。GitHub 官方  PS：这是java库。做网页爬虫（Crawler,Robot）必备。
toml:这是个跨语言的配置信息存取方案。GitHub
Androiton-Action-Bar-Icons:一个针对Android 优化过的ICON图标集。 GitHub Demo
推荐一个Android整体框架：ThinkAndroid 集成了ioc，orm，下载，缓存等模块，能让开发更加快速和高效，同时还是国人项目。GitHub
如果你想要更快的网络传输和加载速度可以试试OKHTTP，他实现了Google开发的SPDY协议，通过复用一个Socket，缩短网络加载时间。关于SPDY看这里  OKHTTP
Android-ProgressFragment:等待数据的时候，支持显示等待符号的Fragment控件。GitHub
关于播放视频，不要再去研究什么FFMPEG了，too slow，国人有个非常非常出色的开源项目叫Vitamio，让你播放视频简单如abc。GitHub 官方网站
AndroidCommon:Android常用的一些库和功能，如缓存，下拉列表，下载管理，静默安装等。感谢Trinea GitHub
ion: 让Android的网络操作变得极其简单，支持异步获取和处理JSON，支持Android文件下载（同时支持下载进度条绑定），支持安全链接和代理。超级推荐！ GitHub
IcePick: onSaveInstance的辅助类，用于快速恢复Activity状态。GitHub
四、图标资源：

http://iconsparadise.com/ 质量一般，但也是一种选择
http://iconbench.com/ 在线产生一些小图标
http://www.androidicons.com/ 图标质量很不错，但是要付费($25刀)，如果有想合买的可以联系我~
https://code.google.com/p/android-ui-utils/  用来在线生成符合Android Design风格的设计图标。 项目地址
http://www.flaticon.com/ 高质量矢量图，推荐之~
http://subtlepatterns.com/ 背景素材集合
Android-Iconify:一个将AweomeICON和Android结合起来的项目，推荐。
IonIconView：Android下的一个基于AwesomeICON的图标组件，力荐~ 
五、一些手册

Android图形界面设计手册，可以用来快速查看图标的大小、ActionBar的Height等琐碎的Android Design要求。GitHub
Android 官方UI设计手册：下载 另：中文翻译版本 源地址 （需要梯子） 镜像1、镜像2、镜像3 离线版本打包   项目发起人：SunJW （需要梯子）
七、一些视频（以下均为Google 2013 I/O大会的现场视频，视频较多持续更新中…）

Android Studio 的新特性官方讲解视频，我在官方技术博客上下载下来，上传到网盘，希望对大家有帮助。下载地址
Android引入Gradle的官方讲解视频 下载地址。
Google 2013 IO大会上抽出40多分钟时间讲解了Android Custom View的底层原理和书写方法。非常值得一看！下载地址。
IO大会上还讲解了高性能Android RenderScript的原理和使用方法，搞图形图像必备良品。下载地址
大会上还向开发者讲解了如何实现简洁、快速的网络请求。包括常用的JSON、AsyncTask，还提出了一种网络负荷较重情况下的解决方案RequestQueue（请求队列），提升自己技术必备视频。下载地址
Android 蓝牙 操作最佳实践。下载地址
Android ui 设计官方指南 下载地址
Android游戏开发 官方讲解视频 下载地址
八、高价值链接

Android官方博客 提供一些跟Android相关的即时咨询。（需要梯子）
Android官方技术博客 主要提供一些新工具（如Android Studio），新技术（如每次更新带来新特性）的演示和讲解。（需要梯子）
23code.com: 超强烈推荐，里面收集了非常多漂亮的Android开源项目。
StylingAndroid: 时常介绍Android的新特性。
AndroidViews Android View组件收集站点。
那两年炼就的Android内功修养 (这是一篇Android入门到提高的文章，内容很全面，而且由浅入深，强烈推荐，来自老罗的Android之旅)
Android-er :专注Android好多年的一个老外的Blog。（需要梯子）
Android-Pattern:Android的一些设计模式。
Android-Nicetices:博客收录了很多优秀的Android设计样式。
Android-Newbie: 收录了Android图像处理相关的教程。
MooDroid: 我创办的另一个关于Android 开源库的分享站点。
Chris Banes: 很酷！
九、集成其他开发特性(懒人专用)

ORM： Object-relationship mapping，如果你不知道什么是ORM设计，Google。 目前Android上主要有三个ORM开源库。greenDAO 、OrmLite、AndrORM。排序基本代表性能。greenDao和Ormlite性能测试  Ormlite和Androrm性能对比，主要是原理实现决定的性能差异（GreenDao采用生成数据表类文件，其他的则采用了反射…）。如果对数据库性能要求很高，那么采用greenDao，如果想图方便采用OrmLite或者AndrORM。
ORM2: ActiveAndroid，另一个Android ORM组件，做的非常棒，推荐。GitHub
sprinkles: 有一个ORM组件。 GitHub
android-priority-jobqueue：Android Job队列。轻松实现后台task管理，保证代码更清晰，低耦合。GitHub
androidquery: 简单的Android框架，让写代码变得更简单。Google Code
Android-Templates-And-Utilities: 集合了Android开发中一些常用的工具类和模板以及一些代码片段。GitHub
Android key value 引擎： MooDroid
十、专注Android的Blog

http://www.trinea.cn/ 关注Android性能还有一些小细节的，感谢VilenEera推荐。
http://blog.csdn.net/jj120522 解决很多关于Android生产环节的开发细节，感谢star的推荐。
https://github.com/Trinea/android-open-project 由Trinea收集的很多关于Android第三方特征库的Repo。
http://linkyan.com/ 就职于花瓣，专注于Android。
十一、有用的Android Studio 和 Eclipse插件

android-parcelable-intellij-plugin: 快速为类实现Parcelable接口。 GitHub
sdk-manager-plugin: 自动下载和安装缺失的SDK和依赖库，建议所有开源项目集成，使得第三方更加容易编译。GitHub
android_dbinspector：开发过程中经常要看数据库的结构和数据库内容，这个第三方工具就能快速帮助你完成所有数据库校验工作。GitHub
AndroidStudioTemplate：开发过程中，帮助你快速创建一些开发模板。GitHub
十二、从这些项目中学习组件的用法

repay-android : 一个和朋友之间管理账务的App，做的很精致。
Android-GitHub: GitHub官方Android客户端（感谢Liu Chong推荐），用到了以下几个项目：
ActionBarSherlock
ViewPagerIndicator
RoboGuice
android-maven-plugin
CodeMirror
十三、有用文章收集

提交AAR包到Maven center. Link Link2
文章类型：原创

最后更新时间：2014-06-12

文章标题：Android 开源库

作者：代码家  ，转载请注明出处。

协议：Creative Common

捐助：此渣文如果对你有帮助的话，考虑来一发小额捐助如何！

支付宝 扫一扫右侧二维码即可完成捐助：

 
