## 我的前端路程

从大三初开始接触前端内容，到现在已不知不觉过了近三年时间，痛并快乐着，现今每天都在和前端的相关东西打交道，也算是对这一行有一些了解。

#### 原型设计

前端学一些设计还是非常有必要，素描绘画/ps/AI/原型图绘制，这一阶段被认知为培养美的阶段，至少我们知道什么样的东西是漂亮的，虽然可能真正到了敲代码的时候，我们可能更多的只是切图，量尺寸、吸颜色 。

#### html+css

最初我们可能需要写一个静态页面，没有任何动画，只需要用div+css布局方式构建一个静态页面，比如会写一个天猫首页、京东首页、小米官网、锤子官网、银泰官网等等，因为电商类页面较为复杂，是最好熟练技能的方式。 

#### 原生javascript/es6

然后某一天开始学习JavaScript，知道Javascript可以写很多动画、ajax数据交互、正则校验、处理业务逻辑等等，然后这时候我们将之前写好的静态页面添加动画效果，让其变得“动”起来。

#### jquery

用原生js写了一遍动画效果之后，某一天突然接触到了jquery，感觉方便到不行，只需要引入这个库，写出的代码量更少，更为方便

#### sass/less/stylus

然后接触到了sass/less，用函数的思想来写css，动态计算、封装公用样式更为方便

#### vue/react/angular

前端主流三大框架，不再是用jquery直接操作DOM，采用MVVM开发模式、双向数据绑定、单页面...

#### react native/weex

主要是开发APP时用，用前端技术开发接近于原生的混合型APP，react native由facebook开发基于react,weex 由阿里开发基于vue 目前我还没涉及到该方面的内容。

#### node/webpack

接着就是node/npm/webpack/mysql  工程化的开发流程，我们甚至可以自己开发接口，自己来调用，引入npm包管理工具，可以下载项目中想要依赖的几乎任何库，webpack自动化构建工具，编译、静态代码分析（JSLint、CSS Lint、TSLint）、对代码质量进行分析等

#### git/svn

版本控制工具，用于监听代码修改，目前用git较多，创建分支、提交代码、合并到master上，可用命令行，也可用软件管理(sourcetree)

详细命令可查看git相关教程，遇到代码冲突不要走便捷，一定要挨个查看解决，目前我常用的命令有：

```
git status

git add .

git status

git commit -m '修改'

git push
```

## 前端开发历程

最初的前端可能就是把UI人员提供的设计稿用html+css+js写一个有动画效果的页面就算OK了，剩下便把东西丢给后端，加到后端开发目录中，让后端来套数据、发布上线。（那个时候可能大家用的框架都是MVC框架）（主要开发模式有MVC / MVVM / MV*这三种），那时候的前端可能并不被称为一名程序员，或许归到了设计师的范畴？

但现在前端人员所做的东西可能远远不止写一个静态页面（可能有一些动效）那么简单，PC、WAP、小程序甚至APP开发，无不留下前端开发的影子...

甚至当node出现之后，好像前端也可以干后端干的活，数据库、用JavaScript这门语言处理后端的业务逻辑，前端已然变成“全栈开发”

## 前端相关资源

#### 设计网站 
* [uigreat](http://www.uigreat.com/) 
* [花瓣网](http://huaban.com/)  
* [dribbble](https://dribbble.com/)  
* [behance](https://www.behance.net/) 
* [pinterest](https://www.pinterest.com/) 
* [站酷](https://www.zcool.com.cn/) 
* [FWA](https://thefwa.com/)

有朝一日我们自己构建网站的时候，可以来这儿找找素材，让我们写的页面更为美观~

#### html/css/js/react/vue/node/es6

如果要学习html/css/js...的时候，可以先去[菜鸟教程](http://www.runoob.com/) 过一遍其中的知识点，当然也可去网易云课堂、慕课网、腾讯课堂找一找相关的视频教程。有时候时候看文档不思其解的时候，可以去看看视频。看文档学习速度比较快，而看视频更为直观，易于发现问题，二者各有优势。

[印记中文](https://www.docschina.org/)  该网站链接了几乎所有前端主流开发技术的中文文档，如果找不到文档了，可以来这儿搜搜

* (vue项目练习项目) (https://github.com/vuejs/awesome-vue)

* (react练习项目) (https://github.com/enaqx/awesome-react)

一般找一些框架资源时，可去github上搜索：awesome + 对应框架名 找star数最多的仓库，会是关于这个框架收集的一些好的练习项目。

#### BootCDN

[BootCDN](https://www.bootcdn.cn/) 在bootstrap cdn上可以搜到几乎所有的开源库，例如jquery/echarts/vue/bootstrap/swiper...，我们可以下载到本地，也可以直接引用cdn地址，毕竟，cdn的访问速度比从项目目录中引用要快

#### 代码托管网站

* [github](https://github.com) 

国际开源网站，几乎所有的开源项目、框架都可以在其上找到；前端也可以利用其做个人项目的积累，github pages提供页面访问服务，我们发布上去的静态页面可以直接在线访问；我的个人博客，大多数的兴趣练习内容也都放在github上  (https://github.com/gwemz)  github提供自定义域名，例如：http://gwem.tk  在项目目录中新建一个CNAME文件，将域名解析到该仓库的ip上，你便拥有了一个对外的网站，虽然可能没有数据库，但某些时候也是非常方便。 某些时候在面试的时候，也会看github上的提交记录，看看有没有开源的优秀代码

* [coding](https://coding.net/) 

国内代码托管商，可创建私有仓库，不过比较少，如果要升级，需要开通会员。公开仓库可随意创建。访问地址在微信中会经过一个coding的中间页，不太友好。

* [码云gitee](https://gitee.com/) 

国内代码托管网站，个人用户可创建至多1000多私有仓库，可对外部署访问。域名在微信中可访问，不会被转掉，推荐私有仓库可选择它。

* [语雀](https://www.yuque.com/) 

语雀并不是一个代码托管的网站，它类似于印象笔记，不过借鉴了github的产品思想，是一个编辑保存文档的轻量产品，原为阿里内部系统，后对外开放 可记录一些好的点子，或者是心得体会

#### IDE（编辑器）

* [vscode](https://code.visualstudio.com/) 

    免费软件，由微软开发。现今最好用的编辑器，没有之一，启动速度快，内置git版本记录，丰富的插件库 

在之前我们可能还会使用sublime、webstorm、atom等等一系列编辑器，但自从vscode出现之后，都卸载了...

#### 调试工具

chrome 浏览器调试工具，主流的浏览器厂商主要是IE、Chrome、Firefox、safrial，不过现在做前端开发几乎都用chrome来调试了（pc/wap），关于调试工具用法可查看视频，或者是某一些博文，可以快速定位问题。

#### 常去的网站

对我而言，常去的社区主要有 
* [掘金](https://juejin.im/) 
* [segmentfault](https://segmentfault.com/) 
* [github](github.com)
* 更多感兴趣的可去[web前端导航](http://www.alloyteam.com/nav/) 查看推荐

#### 字体图标库

* [阿里巴巴矢量图标库](http://iconfont.cn/)  

    可以直接将图标以代码的方式引入，减少开发空间 当然在个人项目，可以找自己感兴趣的图标

#### 图片压缩网站

* [tinypng](https://tinypng.com/)  

    嗯，没错，就是这只贱贱的熊猫

#### UI库

* [bootstrap](http://www.bootcss.com/) 

    最早的UI库，自适应，快速构建页面，不需要考虑样式

* [bulma](https://bulma.io)  

    bootstrap如果看腻了，可以用这个UI库看看

* [ant-design](https://ant.design/index-cn) 

    由阿里推出，主要在react项目中使用

* [element](http://element-cn.eleme.io/#/zh-CN) 

    饿了么推出，主要在vue项目中使用

* [cube-ui](https://didi.github.io/cube-ui/) 

    由滴滴开发，主要在vue项目中使用

#### 前端书籍推荐

* JavaScript权威指南  
* JavaScript高级程序设计   
* JavaScript设计模式与开发实践  
* HTTP权威指南

大部分都是关于javascript，因为这门语言在前端开发中所占的权重最终，虽然本人看的比较少，但也强烈推荐。

#### 前端公众号

公众号看的比较少，主要会关注 `前端早读课`  `前端大全` ，因为以我的习惯，关注的太多也很少去看，还不如关注少一些，偶尔还会看看，会发布关于前端的一些动向。

#### 前端大牛（china）

* [尤雨溪](https://github.com/yyx990803)  

    vue框架的作者

* [阮一峰](https://github.com/ruanyf) 

    可以看看他的github,全年不断更是什么感觉，密密麻麻，翻译了《ECMAScript 6入门 、flex布局教程等等，讲解非常详细，目前国内github排名第一，[语雀地址](https://www.yuque.com/ruanyf)  [个人网站官网](http://www.ruanyifeng.com/)

* [phodal](https://github.com/phodal) 

    大牛一枚，写框架、翻译书、github社区非常活跃，不过对我而言，最为羡慕的便是github上的签名“待我代码编成，娶你为妻可好” 浪漫到不行。

* [gihub中国开发者排名](http://www.githubrank.com/)

#### 关于问题搜索

谷歌搜索，嗯，就是这样 大大提高搜索效率，实在不行就用必应，现阶段遇到的问题几乎网络都可以找到，除非遇到的技术比较新

如果是小程序的项目，可以去微信官方社区看看，大多时候可以找到，找到一堆吐槽。。。

当然学习的目的是为了能够在某一处能够运用的上，一定要多多练习，自我感觉很多时候我们缺少的并不是资源，而是学习的持续性。

## 前端三大框架

提起前端，不得不提现今前端三大主流框架：Angular、React、Vue 三足鼎立之势 

传统开发属于MVC模式开发，即项目开发目录都在后端那里，后端用模板将数据返回前台页面进行遍历渲染，例如java框架freemarker，php框架phpcms都属于类似的开发模式。（当然传统框架离不开一个前端JS库，jquery -》 直接操作DOM）而现今前后端分离之后，前端体系日趋成熟，前后端分离，前端出现了三大框架，主要采用MVVM方式开发，双向数据绑定、单页面、逻辑层与视图层分离，很是方便

Angular 为谷歌推出，前两年较为火热，现今使用量很少 不推荐

React 为facebook推出，目前国内大公司几乎都是基于React做开发，例如阿里系、腾讯系等等

Vue 为前端大牛 [尤雨溪](https://github.com/yyx990803) 开发，学习成本较前两个框架低，目前使用人数也是非常多，中文文档健全，毕竟是国人开发，习惯也比较接近

前端开发主要由html + css + javascript语言开发而成，现今前端变化很快，但也都是基于这三种语言做升级、开发流程工程化、更为便捷

html 嗯，页面结构构成元素 两天左右便可把html所涉及所有标签过一遍 （html5、html4）一般在布局时，也没有特殊要求，不过为了SEO优化，需要在写页面结构的时候采用合理化的标签

css css3 修改页面样式 将页面渲染更为美观 目前布局方式table布局（几乎不用）、盒子布局(浮动float PC、wap 不需要考虑兼容性，几乎主流浏览器都支持)、flex布局（弹性布局，移动端布局使用，目前PC端支持并不那么广，虽然其很好用）

javascript  处理页面动画、数据交互、业务逻辑等等  目前最为前沿版本是ES6 （阮一峰ES6教程）、ES7，新语法特性，不过浏览器对新技术支持不太友好，需要利用babel将新语法转换为es5相关语法

不管是PC、WAP、小程序、混合型APP，目前打交道的也都是这三门语言，所以前端入门比较容易 但要深入，请牢记，任重道远。

## 项目开发流程

然后聊聊项目开发流程，一般在一个比较完整的项目开发流程中，首先是产品提出设想，原型图、需求文档，产品内部评审（主要是剔除一些鸡肋功能以及奇葩想法）；

没有问题之后提出需求，然后前端、后端、设计、产品、领导聚集在一块儿，大家开个会，各抒己见；

之后便进入开发阶段，各个部门评估项目所需时间、预计上线日期... 

嗯，接着UI开始了设计、后台开始写接口、前端开始写页面，看似很美好... 最开始前端好像没什么活，因为好像什么都没有。设计稿完工之后便开始写静态页面，顺便加点设计想要的效果 OK，写好了

某一天后台开发也把接口写好了，你便开始获取数据，交互、写业务逻辑了

当数据全部套完之后，各种功能也都实现完成，自测也差不多，然后便交给测试人员做测试

然后便开始了改bug的辛酸路程，测试和开发互怼的过程，嗯，当所有都改的差不多之后，将开发分支合到master分支，准备上线了。。。

上线之后完成修改以及bug修改等等

嗯，正常的一个流程便大体如此，当然项目时间拖延也是经常遇到的情况，对前端而言，比如设计、后台接口没有在规定时间内完成，然后你就痛苦了，因为前端往往是最先开始也是最后结束一个工种，这个时候要想在整个项目的预计时间内上线，就得加班加点了，便开始顶着大大的黑眼圈，眼都不眨的盯着屏幕码代码了。。。

偶尔加班到11点多，12点多，1点多好像很正常，在一心一意做开发的时候好像时间过得很快，直到某一个问题把你卡住，心里边就像有一万只蚂蚁爬过... 不过好像对一只单身狗而言，加班有时候也是派遣寂寞的方式，好像回去也没什么事可干，还不如在公司，夏天蹭一蹭空调，冬天蹭一蹭空调...

如果感觉开发比较痛苦，大致有三种原因，一：你对你所用的技术不熟，不知道用什么方法实现这个功能，即便你的脑中有思路  二：你没明白你到底要做什么（需求没理解）  三：实现这个功能比较复杂，太耗神~

很烦躁的时候回答问题，经常会口无遮拦，说一些并非自己本意的东西。所以，现在也会形成一套官方用语，我先看看~  有些时候确实是把问题想复杂了，其实解决很快，静心码代码，有时候时间过的确实非常的快

## 小程序开发流程

小程序项目开发和wap、pc基本相同，在我看来小程序开发更为容易，微信提供了很多API，可以非常方便的实现业务逻辑，几乎只需要专注业务就可

小程序开发完成之后会有微信审核这一步，正常2到3个小时，多一些可能需要一天时间，可能需要合理规划开发时间

另外如果上线之后发现遇到bug，可以版本回退，至多回退2个版本，以规避某一些测试没有发现的问题

## 结语

在最开始写这一篇总结的时候，比较懵，好像做了这么久的前端，也并没有认真去想到底用到了什么？有这一个契机，让我有机会去想想这个问题，对我也是一个总结、一次学习。7000多字，好像很久没写这么多了。(日常写文档基本上用markdown语法书写，对开发者而言，简洁、方便的文档编写语言)