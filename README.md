### 十九届六中全会精神

党的十八大以来，在党中央、中央军委和习近平主席坚强领导下，人民军队全面实施改革强军战略，开展了一场新中国成立以来最为广泛、最为深刻的国防和军队改革，实现整体性革命性重塑。党的十九届六中全会通过的《中共中央关于党的百年奋斗重大成就和历史经验的决议》，充分肯定深化国防和军队改革取得的历史性成就，对于动员全党全军聚力推进改革强军，奋力实现党在新时代的强军目标、把人民军队全面建成世界一流军队，具有重大而深远的意义。

# Editor.md

![](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png)

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)

**目录 (Table of Contents)**

[TOCM]

[TOC]

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
# Heading 1 link [Heading link](https://github.com/pandao/editor.md "Heading link")
## Heading 2 link [Heading link](https://github.com/pandao/editor.md "Heading link")
### Heading 3 link [Heading link](https://github.com/pandao/editor.md "Heading link")
#### Heading 4 link [Heading link](https://github.com/pandao/editor.md "Heading link") Heading link [Heading link](https://github.com/pandao/editor.md "Heading link")
##### Heading 5 link [Heading link](https://github.com/pandao/editor.md "Heading link")
###### Heading 6 link [Heading link](https://github.com/pandao/editor.md "Heading link")

#### 标题（用底线的形式）Heading (underline)

This is an H1bb
=============

This is an H2
-------------

### 字符效果和横线等
                
----

~~删除线~~ <s>删除线（开启识别HTML标签时）</s>
*斜体字*      _斜体字_
**粗体**  __粗体__
***粗斜体*** ___粗斜体___

上标：X<sub>2</sub>，下标：O<sup>2</sup>

**缩写(同HTML的abbr标签)**

> 即更长的单词或短语的缩写形式，前提是开启识别HTML标签时，已默认开启

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.

### 引用 Blockquotes

> 引用文本 Blockquotes

引用的行内混合 Blockquotes
                    
> 引用：如果想要插入空白换行`即<br />标签`，在插入处先键入两个以上的空格然后回车即可，[普通链接](http://localhost/)。

### 锚点与链接 Links

[普通链接](http://localhost/)

[普通链接带标题](http://localhost/ "普通链接带标题")

直接链接：<https://github.com>

[锚点链接][anchor-id] 

[anchor-id]: http://www.this-anchor-link.com/

GFM a-tail link @pandao

> @pandao

### 多语言代码高亮 Codes

#### 行内代码 Inline code

执行命令：`npm install marked`

#### 缩进风格

即缩进四个空格，也做为实现类似`<pre>`预格式化文本(Preformatted Text)的功能。

    <?php
        echo "Hello world!";
    ?>
    
预格式化文本：

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

#### JS代码　

```javascript
function test(){
	console.log("Hello world!");
}
 
(function(){
    var box = function(){
        return box.fn.init();
    };

    box.prototype = box.fn = {
        init : function(){
            console.log('box.init()');

			return this;
        },

		add : function(str){
			alert("add", str);

			return this;
		},

		remove : function(str){
			alert("remove", str);

			return this;
		}
    };
    
    box.fn.init.prototype = box.fn;
    
    window.box =box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```

#### HTML代码 HTML codes

```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>
```

### 图片 Images

Image:

![](https://pandao.github.io/editor.md/examples/images/4.jpg)

> Follow your heart.

![](https://pandao.github.io/editor.md/examples/images/8.jpg)

> 图为：厦门白城沙滩

图片加链接 (Image + Link)：

[![](https://pandao.github.io/editor.md/examples/images/7.jpg)](https://pandao.github.io/editor.md/examples/images/7.jpg "李健首张专辑《似水流年》封面")

> 图为：李健首张专辑《似水流年》封面
                
----

### 列表 Lists

#### 无序列表（减号）Unordered Lists (-)
                
- 列表一
- 列表二
- 列表三
     
#### 无序列表（星号）Unordered Lists (*)

* 列表一
* 列表二
* 列表三

#### 无序列表（加号和嵌套）Unordered Lists (+)
                
+ 列表一
+ 列表二
    + 列表二-1
    + 列表二-2
    + 列表二-3
+ 列表三
    * 列表一
    * 列表二
    * 列表三

#### 有序列表 Ordered Lists (-)
                
1. 第一行
2. 第二行
3. 第三行

#### GFM task list

- [x] GFM task list 1
- [x] GFM task list 2
- [ ] GFM task list 3
    - [ ] GFM task list 3-1
    - [ ] GFM task list 3-2
    - [ ] GFM task list 3-3
- [ ] GFM task list 4
    - [ ] GFM task list 4-1
    - [ ] GFM task list 4-2
                
----
                    
### 绘制表格 Tables

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机      | $1600   |   5     |
| 手机        |   $12   |   12   |
| 管线        |    $1    |  234  |
                    
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell 

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Function name | Description                    |
| ------------- | ------------------------------ |
| `help()`      | Display the help window.       |
| `destroy()`   | **Destroy your computer!**     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

| Item      | Value |
| --------- | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |
                
----

#### 特殊符号 HTML Entities Codes

&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot; 

X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;

18&ordm;C  &quot;  &apos;

### Emoji表情 :smiley:

> Blockquotes :star:

#### GFM task lists & Emoji & fontAwesome icon emoji & editormd logo emoji :editormd-logo-5x:

- [x] :smiley: @mentions, :smiley: #refs, [links](), **formatting**, and <del>tags</del> supported :editormd-logo:;
- [x] list syntax required (any unordered or ordered list supported) :editormd-logo-3x:;
- [x] [ ] :smiley: this is a complete item :smiley:;
- [ ] []this is an incomplete item [test link](#) :fa-star: @pandao; 
- [ ] [ ]this is an incomplete item :fa-star: :fa-gear:;
    - [ ] :smiley: this is an incomplete item [test link](#) :fa-star: :fa-gear:;
    - [ ] :smiley: this is  :fa-star: :fa-gear: an incomplete item [test link](#);
 
#### 反斜杠 Escape

\*literal asterisks\*
            
### 科学公式 TeX(KaTeX)
                    
$$E=mc^2$$

行内的公式$$E=mc^2$$行内的公式，行内的$$E=mc^2$$公式。

$$\(\sqrt{3x-1}+(1+x)^2\)$$
                    
$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

多行公式：

```math
\displaystyle
\left( \sum\_{k=1}^n a\_k b\_k \right)^2
\leq
\left( \sum\_{k=1}^n a\_k^2 \right)
\left( \sum\_{k=1}^n b\_k^2 \right)
```

```katex
\displaystyle 
    \frac{1}{
        \Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{
        \frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {
        1+\frac{e^{-6\pi}}
        {1+\frac{e^{-8\pi}}
         {1+\cdots} }
        } 
    }
```

```latex
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
```
                
### 绘制流程图 Flowchart

```flow
st=>start: 用户登陆
op=>operation: 登陆操作
cond=>condition: 登陆成功 Yes or No?
e=>end: 进入后台

st->op->cond
cond(yes)->e
cond(no)->op
```
                    
### 绘制序列图 Sequence Diagram
                    
```seq
Andrew->China: Says Hello 
Note right of China: China thinks\nabout it 
China-->Andrew: How are you? 
Andrew->>China: I am good thanks!
```

### End
<!DOCTYPE html>
<html lang="en" class="">
<head>
<meta http-equiv="Cache-Control" content="no-cache" />
<meta http-equiv="content-type" content="text/html;charset=GB2312"/>
<meta http-equiv="Content-Language" content="utf-8" />
<meta name="format-detection" content="telephone=no, email=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="white">
<title>聚焦十九届六中全会--专题报道--人民网</title>
<meta name="renderer" content="webkit">
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
<meta name="keywords" content="" />
<meta name="description" content="" />
<meta name="catalogs" content="441273" />
<meta name="filetype" content="1" />
<meta name="publishedtype" content="1" />
<meta name="pagetype" content="2" />
<meta name="screen-orientation" content="portrait">
<meta name="x5-orientation" content="portrait">
<meta name="full-screen" content="yes">
<meta name="x5-fullscreen" content="true">
<meta name="browsermode" content="application">
<meta name="x5-page-mode" content="app">
<link charset="utf-8" rel="stylesheet" href="/img/MAIN/2021/02/120755/css/animate.min.css" inline>
<link rel="stylesheet" href="http://tools.people.com.cn/libs/swiper/2.0/idangerous.swiper.css">
<link charset="utf-8" rel="stylesheet" href="/img/MAIN/2021/11/121189/mainh.css" inline>
<script charset="utf-8" src="http://tools.people.com.cn/libs/jquery/1.11.1/jquery-1.11.1.min.js" inline></script>
<script src="http://tools.people.com.cn/libs/swiper/2.0/idangerous.swiper.min.js"></script>
</head>
<body>
<div class="main" id="app">
<div class="video-box clearfix"><video id="fmh" src="http://flv4.people.com.cn/videofile7//pvmsvideo/2021/11/6/QuanMeiTiZhiZuoErBu-YanChuanJiYu_5f85fa91b3a5cdb62937a5ab5d7c10d9.mp4" autoplay muted loop x5-playsinline="true" x5-video-player-fullscreen="true" preload="auto" x5-video-orientation="portrait" playsinline="true" webkit-playsinline="true" x-webkit-airplay="true" x5-video-player-type="h5"></video><img src="/img/MAIN/2021/11/121189/images/outv.png" class="outsp" /></div>
<script type="text/javascript">
var myVideo = $(".video-box video")[0]
var cishu = 0;

if (myVideo && !/Android|iPhone|iPad/i.test(navigator.userAgent)) {
	myVideo.addEventListener("timeupdate", function (e) {
	  if (e.target.currentTime > 8.9) {
		e.target.currentTime = 4
	  }
	  if (e.target.currentTime < 8.9 && e.target.currentTime > 7 && cishu == 0) {
		$('html,body').animate({ scrollTop: $(".nav").offset().top }, 500); 
		cishu = 1;
	  }
	}, false);

	myVideo.onerror = function () {
	  myVideo.style.display = 'none'
	};
}
setTimeout(function () {
	
	var ua = navigator.userAgent;
	var ipad = ua.match(/(iPad).*OS\s([\d_]+)/),
	  isIphone = !ipad && ua.match(/(iPhone\sOS)\s([\d_]+)/),
	  isAndroid = ua.match(/(Android)\s+([\d.]+)/),
	  isMobile = isIphone || isAndroid || ipad;
	if (isMobile) {
	  document.body.className = 'phone'
	  $(".video-box").hide()
	}
	if (window.innerWidth / window.innerHeight < 1) {
	  document.body.className = 'phone'
	  $(".video-box").hide()
	}
}, 0);
$(document).ready(function () {
	setTimeout(function () {
	  $(window).scrollTop(0);
	}, 400);
	$(".outsp").bind('click', function (event) {
		$('html,body').animate({scrollTop: $(".nav").offset().top}, 500);
	})
});
</script>
<div class="nav clearfix">
	<div class="w1200">
		<span><img src="/img/MAIN/2021/11/121189/images/logo.png" /></span><em><a href="#yaowen">要闻</a><a href="#cehua">策划</a><a href="#video">视频</a><a href="#fendou">百年奋斗历程</a><a href="#ziliao">文件资料</a></em>
	</div>
</div>
<div class="bgsp yellow clearfix">
<a id="yaowen" name="yaowen"></a>
<div class="w1200 news mt40 clearfix">
<h1><a href='/n1/2021/1117/c64387-32284363.html' target=_blank>中共中央关于党的百年奋斗重大成就和历史经验的决议</a></h1>

<p><a href='/n1/2021/1116/c64094-32284171.html' target=_blank>习近平：关于《中共中央关于党的百年奋斗重大成就和历史经验的决议》的说明</a>
<a href='/n1/2021/1117/c64387-32285124.html' target=_blank>决议诞生记</a>
<a href='/n1/2021/1113/c64036-32281266.html' target=_blank>中共十九届六中全会在京举行</a>
<a href='/n1/2021/1111/c64387-32280050.html' target=_blank>公报</a>
<a href='/n1/2021/1113/c64093-32281297.html' target=_blank>侧记</a>
<a href='/n1/2021/1112/c64387-32280282.html' target=_blank>与会同志谈党的十九届六中全会精神</a>
</p>
</div>
<div class="w1200 p1con mt40 clearfix">
	<div class="fl">
		<div class="swiper-container-p1 white">
	<div class="swiper-wrapper"><div class="swiper-slide"><a href="http://pic.people.com.cn/n1/2021/1111/c426981-32280080.html" target=_blank><img src="/NMediaFile/2021/1113/MAIN202111131323119175073206317.jpg" width="790" height="480" alt="中国共产党第十九届中央委员会第六次全体会议在北京举行&#13;"/></a><span><a href="http://pic.people.com.cn/n1/2021/1111/c426981-32280080.html" target=_blank>中国共产党第十九届中央委员会第六次全体会议在北京举行
</a></span></div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/n1/2021/1116/c64387-32283532.html" target=_blank><img src="/NMediaFile/2021/1116/MAIN202111160944407456445518358.jpg" width="790" height="480" alt="从公报中读出“昨天、今天、明天”的深意&#13;"/></a><span><a href="http://cpc.people.com.cn/n1/2021/1116/c64387-32283532.html" target=_blank>从公报中读出“昨天、今天、明天”的深意
</a></span></div>
<div class="swiper-slide"><a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281222.html" target=_blank><img src="/NMediaFile/2021/1126/MAIN202111260956360248579703712.JPG" width="790" height="480" alt="栗战书主持全国人大常委会党组会并讲话"/></a><span><a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281222.html" target=_blank>栗战书主持全国人大常委会党组会并讲话</a></span></div>
<div class="swiper-slide"><a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281223.html" target=_blank><img src="/NMediaFile/2021/1126/MAIN202111260956363735750507233.JPG" width="790" height="480" alt="汪洋主持全国政协党组理论学习中心组集体学习并讲话"/></a><span><a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281223.html" target=_blank>汪洋主持全国政协党组理论学习中心组集体学习并讲话</a></span></div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/n1/2021/1119/c64036-32286390.html" target=_blank><img src="/NMediaFile/2021/1126/MAIN202111260956367211161368575.JPG" width="790" height="480" alt="王沪宁出席学习贯彻党的十九届六中全会精神中央宣讲团动员会并讲话"/></a><span><a href="http://cpc.people.com.cn/n1/2021/1119/c64036-32286390.html" target=_blank>王沪宁出席学习贯彻党的十九届六中全会精神中央宣讲团动员会并讲话</a></span></div>
<div class="swiper-slide"><a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281224.html" target=_blank><img src="/NMediaFile/2021/1126/MAIN202111260956370773816310980.JPG" width="790" height="480" alt="赵乐际主持中央纪委常委会深入学习贯彻党的十九届六中全会精神"/></a><span><a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281224.html" target=_blank>赵乐际主持中央纪委常委会深入学习贯彻党的十九届六中全会精神</a></span></div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441273/441480/index.html" target=_blank><img src="/NMediaFile/2021/1126/MAIN202111260956356900824854423.JPG" width="790" height="480" alt="中共中央举行新闻发布会 介绍党的十九届六中全会精神"/></a><span><a href="http://cpc.people.com.cn/GB/67481/441273/441480/index.html" target=_blank>中共中央举行新闻发布会 介绍党的十九届六中全会精神</a></span></div>
</div>
	<div class="swiper-pagination1"></div>
	<div class="prev1"></div>
	<div class="next1"></div>
	<div class="num1">
		<i><em class="thisp"></em>/<em class="allp"></em></i>
	</div>
</div>
	</div>
	<div class="fr">
		<h2><a href="http://opinion.people.com.cn/n1/2021/1229/c1003-32319344.html" target="_blank">深入学习贯彻党的十九届六中全会精神</a></h2><p>进入新时代，党中央、习主席统筹中华民族伟大复兴战略全局和世界百年未有之大变局，着眼实现党在新时代的强军目标，作出改革强军的战略决策，领导人民军队进行了一场具有划时代意义的伟大变革。</p><h2><a href="http://theory.people.com.cn/GB/40557/441506/index.html" target="_blank">人民日报论学习贯彻党的十九届六中全会精神</a></h2><p>党的十九届六中全会从党和国家事业发展的战略全局出发，深入研究党领导人民进行革命、建设、改革的百年历程，全面总结党从胜利走向胜利的伟大历史进程、为国家和民族建立的伟大历史功绩。</p>
		
		<ul class="list1"><li><a href="http://cpc.people.com.cn/GB/67481/441505/index.html" target="_blank">【学习包】党的十九届六中全会学习资料电子书</a></li><li><a href='/n1/2021/1119/c64387-32286667.html' target=_blank>划重点｜学习六中全会精神，这些表述要精读</a></li>
<li><a href="http://cpc.people.com.cn/n1/2021/1112/c64387-32281102.html" target="_blank">党的百年历程中的前两个“历史决议”（上）</a> <a href="http://cpc.people.com.cn/n1/2021/1112/c64387-32281146.html" target="_blank">（下）</a></li><li><a href="http://cpc.people.com.cn/n1/2021/0628/c64387-32142243.html" target="_blank">中国共产党一百年大事记之一</a> <a href="http://cpc.people.com.cn/n1/2021/0629/c64387-32143323.html" target="_blank">之二</a> <a href="http://cpc.people.com.cn/n1/2021/0630/c64387-32144498.html" target="_blank">之三</a></li></ul>
	</div>
</div>
</div>
<a id="xuexi" name="xuexi"></a>
<div class="w1200 tit1 clearfix"><img src="/img/MAIN/2021/11/121189/images/titn0.png" /></div>
<div class="w1200 p2con clearfix" style="display:none;">
	<div class="fl">
		<div class="swiper-container-p4">
<div class="swiper-wrapper"><div class="swiper-slide"><a href="http://cpc.people.com.cn/n1/2021/1117/c64387-32284936.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191044082928235077721.jpeg" width="360" height="525"/></a></div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/n1/2021/1119/c64387-32286994.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191515243728190837108.jpg" width="360" height="525"/></a></div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/n1/2021/1118/c64387-32285848.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191526249971418851417.jpg" width="360" height="525"/></a></div>
</div>
</div>
<div class="prev4"></div>
<div class="next4"></div>
	</div>
	<div class="fr">
		<div class="pic4 white"><div class="clearfix"><a href="http://cpc.people.com.cn/n1/2021/1117/c64387-32284936.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191037257357754534864.jpeg" width="260" height="150"/></a><span><b>这10个“坚持”要牢记</b>
<p>一百年来，党领导人民进行伟大奋斗，在进取中突破，于挫败中奋起，从总结中提高，积累了宝贵的历史经验。以上十个方面，是经过长期实践积累的宝贵经验，是党和人民共同创造的精神财富，必须倍加珍惜、长期坚持，并在新时代实践中不断丰富和发展。</p></span></div>
<ul class="list3 clearfix">
<li><a href='/n1/2021/1114/c64036-32281615.html' target=_blank>深刻理解党百年奋斗的历史意义</a></li>
<li><a href='/n1/2021/1115/c64387-32281969.html' target=_blank>深刻领会党百年奋斗的历史经验</a></li>
<li><a href='/n1/2021/1115/c64387-32282668.html' target=_blank>深刻把握党百年奋斗的重大成就</a></li>
<li><a href='/n1/2021/1116/c64387-32283211.html' target=_blank>深化对新时代党的创新理论的理解和掌握</a></li>
<li><a href='/n1/2021/1117/c64387-32284373.html' target=_blank>深刻领悟加强党的政治建设这个鲜明特征和政治优势</a></li>
<li><a href='/n1/2021/1118/c64036-32285392.html' target=_blank>深刻认识党同人民生死相依休戚与共的血肉联系</a></li>
</ul>
</div>
		<div class="pic4 white"><div class="clearfix"><a href="http://cpc.people.com.cn/n1/2021/1119/c64387-32286994.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191511500782346953069.png" width="260" height="150"/></a><span><b>跟着总书记领悟党的宝贵经验</b>
<p>独立自主是中华民族的优良传统，是中国共产党、中华人民共和国立党立国的重要原则，也是中国外交一以贯之的基本原则。新时代新征程，学习总书记相关讲话，深刻领悟党的百年奋斗历史经验——坚持独立自主，从中汲取智慧和力量，砥砺前行。</p></span></div>
<ul class="list3 clearfix">
<li><a href='/n1/2021/1119/c64387-32286397.html' target=_blank>习近平总书记谋划推动共建“一带一路”述评</a></li>
<li><a href='/n1/2021/1119/c64387-32286358.html' target=_blank>【大道不孤】共建一带一路惠及民生</a></li>
<li><a href='/n1/2021/1115/c64387-32281983.html' target=_blank>【携手同心】团结更多的人共同前进</a></li>
<li><a href='/n1/2021/1116/c64387-32283224.html' target=_blank>【百名外国政党政要看中共】“中国经验为各国探索发展道路提供借鉴”</a></li>
<li><a href='/n1/2021/1116/c64387-32283226.html' target=_blank>【国际论坛】促进世界和平与可持续发展的关键</a></li>
<li><a href='/n1/2021/1118/c64387-32285382.html' target=_blank>【见证·中国机遇】“携手各方实现更大互利共赢”</a></li>
</ul>
</div>
		<div class="pic4 white"><div class="clearfix"><a href="http://cpc.people.com.cn/n1/2021/1118/c64387-32285848.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191531412830261315691.png" width="260" height="150"/></a><span><b>跟着总书记领悟党的宝贵经验</b>
<p>马克思主义是不断发展的开放的理论，始终站在时代前沿。认真学习贯彻习近平总书记关于理论创新的一系列重要论述，对于进一步推进马克思主义基本原理与当代中国实际相结合、永葆中国特色社会主义的生机活力，具有十分重要的现实意义和深远的历史意义。</p></span></div>
<ul class="list3 clearfix">
<li><a href='http://theory.people.com.cn/n1/2021/1119/c40531-32286362.html' target=_blank>在总结党的历史经验中更好开辟未来</a></li>
<li><a href='http://theory.people.com.cn/n1/2021/1118/c40531-32285360.html' target=_blank>坚持党的领导是命脉所在、命运所系</a></li>
<li><a href='http://theory.people.com.cn/n1/2021/1118/c40531-32285347.html' target=_blank>以伟大自我革命引领伟大社会革命</a></li>
<li><a href='http://theory.people.com.cn/n1/2021/1116/c40531-32283179.html' target=_blank>开辟崭新的可持续发展之路的科学指引</a></li>
<li><a href='http://theory.people.com.cn/n1/2021/1118/c40531-32285505.html' target=_blank>【理论圆桌会】如何理解和把握伟大建党精神的内涵？</a></li>
<li><a href='http://theory.people.com.cn/n1/2021/1119/c40531-32286353.html' target=_blank>从百年党史中把握历史规律增强历史主动</a></li>
</ul>
</div>
		
		
	</div>
</div>
<div class="w1200 p2con1 clearfix">
	<div class="pc_news">
	<h2 class="tit3">中央精神</a></h2>
	<ul class="list4"><li><a href='/n1/2021/1113/c64036-32281267.html' target=_blank>中共中央召开党外人士座谈会 习近平主持并发表重要讲话</a></li>
<li><a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281221.html" target="_blank">李克强</a>、<a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281222.html" target="_blank">栗战书</a>、<a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281223.html" target="_blank">汪洋</a>、<a href="http://politics.people.com.cn/n1/2021/1113/c1024-32281224.html" target="_blank">赵乐际主持会议学习贯彻精神</a></li><li><a href='/n1/2021/1119/c64036-32286390.html' target=_blank>王沪宁：全面准确宣讲党的十九届六中全会精神</a></li>
<li><a href='/n1/2021/1119/c64387-32286378.html' target=_blank>丁薛祥：坚定理想信念 牢记初心使命</a></li>
<li><a href="http://politics.people.com.cn/n1/2021/1123/c1001-32289162.html" target="_blank">王晨：继续推动法治中国建设迈出坚实步伐</a></li><li><a href='/n1/2021/1124/c64094-32290259.html' target=_blank>刘鹤：把高质量发展贯穿经济社会发展的各个方面</a></li>
<li><a href='/n1/2021/1125/c64094-32291365.html' target=_blank>李鸿忠：坚决维护党的核心和党中央权威</a></li>
<li><a href='/n1/2021/1126/c64094-32292359.html' target=_blank>杨洁篪：推动构建人类命运共同体</a></li>
<li><a href='http://theory.people.com.cn/n1/2021/1129/c40531-32294081.html' target=_blank>杨晓渡：充分发挥全面从严治党的政治引领和政治保障作用</a></li>
<li><a href='/n1/2021/1130/c64094-32295007.html' target=_blank>张又侠：坚持走中国特色强军之路</a></li>
<li><a href='/n1/2021/1117/c64094-32284384.html' target=_blank>陈希：从党的百年奋斗历史中汲取智慧和力量</a></li>
<li><a href='/n1/2021/1126/c64387-32292472.html' target=_blank>郭声琨：以更高政治站位更紧密联系实际谋划做好政法工作</a></li>
<li><a href='/n1/2021/1125/c64094-32291333.html' target=_blank>黄坤明：进一步深化拓展党史学习教育</a></li>
<li><a href='http://theory.people.com.cn/n1/2021/1203/c40531-32298345.html' target=_blank>肖捷：使人民获得感、幸福感、安全感更加充实、更有保障、更可持续</a></li>
<li><a href='http://theory.people.com.cn/n1/2021/1206/c40531-32300173.html' target=_blank>张庆黎：团结一切可以团结的力量</a></li>
<li><a href='http://theory.people.com.cn/n1/2021/1207/c40531-32301225.html' target=_blank>何立峰：推动全面深化改革向广度和深度进军</a></li>
</ul>
</div>
	<div class="pc_news">
	<h2 class="tit3">学习贯彻</a></h2>
	<ul class="list4"><li><a href='/n1/2021/1214/c64387-32307171.html' target=_blank>中央宣讲团深入各地举行报告会</a></li>
<li><a href='/n1/2021/1210/c64387-32304233.html' target=_blank>学习贯彻党的十九届六中全会精神中央宣讲团宣讲活动综述</a></li>
<li><a href='/n1/2021/1204/c64387-32299367.html' target=_blank>学习贯彻党的十九届六中全会精神中央宣讲团在国防大学宣讲</a></li>
<li><a href='/n1/2021/1204/c64387-32299369.html' target=_blank>学习贯彻党的十九届六中全会精神中央宣讲团在国务院办公厅机关宣讲</a></li>
<li><a href='/n1/2021/1120/c64094-32287362.html' target=_blank>学习贯彻党的十九届六中全会精神中央宣讲团报告会在京举行</a></li>
<li><a href="http://politics.people.com.cn/n1/2021/1209/c1001-32303773.html" target="_blank">各地学习贯彻落实六中全会精神推进全面深化改革开放</a></li><li><a href='http://theory.people.com.cn/n1/2021/1215/c40531-32308193.html' target=_blank>中共中国侨联党组：以六中全会精神引领侨联组织奋进新征程</a></li>
<li><a href="http://politics.people.com.cn/n1/2021/1123/c1001-32289147.html" target="_blank">中宣部举办学习贯彻党的十九届六中全会精神研讨班</a></li><li><a href="http://politics.people.com.cn/n1/2021/1130/c1001-32294913.html" target="_blank">中央宣讲团在中纪委机关</a>、<a href="http://politics.people.com.cn/n1/2021/1130/c1001-32294914.html" target="_blank">浙江</a>、<a href="http://politics.people.com.cn/n1/2021/1130/c1001-32294914.html" target="_blank">江西宣讲</a></li><li><a href='/n1/2021/1126/c64387-32292473.html' target=_blank>中央宣讲团在黑龙江湖北四川甘肃宣讲</a></li>
<li><a href='/n1/2021/1125/c64387-32291340.html' target=_blank>中央宣讲团在上海新疆山东广西西藏青海宁夏宣讲</a></li>
<li><a href='/n1/2021/1124/c64387-32290314.html' target=_blank>中央宣讲团在辽宁吉林安徽福建陕西宣讲</a></li>
<li><a href="http://politics.people.com.cn/n1/2021/1123/c1001-32289146.html" target="_blank">中央宣讲团在广东天津北京内蒙古河南宣讲</a></li><li><a href='/n1/2021/1126/c64387-32292474.html' target=_blank>中央宣讲团在人民日报社宣讲</a></li>
<li><a href="http://cpc.people.com.cn/n1/2021/1122/c64387-32289085.html" target="_blank">庄荣文在人民网宣讲党的十九届六中全会精神</a></li><li><a href='http://theory.people.com.cn/n1/2021/1130/c40531-32295015.html' target=_blank>易炼红：赓续党的红色血脉  弘扬党的优良传统</a></li>
</ul>
</div>
</div>
<a id="cehua" name="cehua"></a>
<div class="w1200 tit1 clearfix"><img src="/img/MAIN/2021/11/121189/images/titn2.png" /></div>
<div class="w1200 p3con clearfix">
	<div class="swiper-container-p3">
	<div class="swiper-wrapper"><div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1111/c64036-32279799.html" target=_blank><img src="/NMediaFile/2021/1111/MAIN202111111516102888378341784.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1111/c64036-32279799.html" target="_blank">“我们是人民的勤务员”</a></b>
<p>在习近平看来，当官，当共产党的“官”，只有一个宗旨，就是造福于民。这些年，无论是在他主持召开的会议上，还是在外出考察调研的行程中，都有大量关乎民生福祉的重要议题。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1110/c64036-32278961.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101904525801108094644.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1110/c64036-32278961.html" target="_blank">“我们这么大一个政党，靠什么来管好自己的队伍？”</a></b>
<p>“打铁必须自身硬。”十八大以来的实践证明，答案只有一个：全面从严治党。习近平十分清醒：“如果管党不力、治党不严，人民群众反映强烈的党内突出问题得不到解决，那我们党迟早会失去执政资格，不可避免被历史淘汰。这决不是危言耸听。”</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1109/c64036-32277996.html" target=_blank><img src="/NMediaFile/2021/1109/MAIN202111092054035636549534220.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1109/c64036-32277996.html" target="_blank">“人民把权力交给我们，我们就必须以身许党许国、报党报国，该做的事就要做，该得罪的人就得得罪。”</a></b>
<p>在习近平看来，“腐败问题对我们党的伤害最大”，若听任不正之风侵蚀党的肌体，“就有失去民心、丧失政权的危险”。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1108/c64036-32276961.html" target=_blank><img src="/NMediaFile/2021/1108/MAIN202111082010331584014639620.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1108/c64036-32276961.html" target="_blank">“我们能不能做到既利用对外开放机遇而又不被腐蚀或吃掉？”</a></b>
<p>习近平指出，我们只有立足自身，把国内大循环畅通起来，努力炼就百毒不侵、金刚不坏之身，才能任由国际风云变幻。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1107/c64036-32275805.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071909371025279913029.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1107/c64036-32275805.html" target="_blank">“为什么说绿水青山就是金山银山？”</a></b>
<p>“谁不愿意到绿水青山的地方来投资、来发展、来工作、来生活、来旅游？从这一意义上说，绿水青山既是自然财富，又是社会财富、经济财富。”习近平在参加十二届全国人大二次会议贵州代表团审议时，道出了生态环境保护和经济发展的良性互动关系。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1106/c64036-32275371.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071639118616549074152.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1106/c64036-32275371.html" target="_blank">“是敌视对立还是相互尊重？是封闭脱钩还是开放合作？是零和博弈还是互利共赢？”</a></b>
<p>70多亿人同在“地球村”，不同民族、不同国家、不同信仰、不同文化如何相处？“构建人类命运共同体，实现共赢共享”。习近平总书记向全世界提出中国方案。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1105/c64036-32275045.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071455329497463693992.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1105/c64036-32275045.html" target="_blank">“我们这支军队能不能始终坚持住党的绝对领导，能不能拉得上去、打胜仗，各级指挥员能不能带兵打仗、指挥打仗？”</a></b>
<p>这三个“能不能”，是习近平的“胜战之问”，也是人民军队战斗力建设必须回答的时代之问。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1104/c64036-32273992.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071500438164721930348.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1104/c64036-32273992.html" target="_blank">“办好这件事，等不得，也急不得。”</a></b>
<p>不急，就要实事求是；不等，就要有所作为。以习近平同志为核心的党中央把逐步实现全体人民共同富裕摆在更加重要的位置上，推动区域协调发展，采取有力措施保障和改善民生，打赢脱贫攻坚战，全面建成小康社会。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1104/c64036-32273692.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071504035522257181059.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1104/c64036-32273692.html" target="_blank">“什么叫人民至上？这么多人围着一个病人转，这真正体现了不惜一切代价。”</a></b>
<p>“在保护人民生命安全面前，我们必须不惜一切代价，我们也能够做到不惜一切代价”，回顾习近平就疫情防控主持召开的会议、作出的指示批示，“人民”始终是最突出的词汇。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1103/c64036-32272824.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071613547962539476459.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1103/c64036-32272824.html" target="_blank">“如果没有中华五千年文明，哪里有什么中国特色？”</a></b>
<p>“一个民族的复兴需要强大的物质力量，也需要强大的精神力量。没有先进文化的积极引领，没有人民精神世界的极大丰富，没有民族精神力量的不断增强，一个国家、一个民族不可能屹立于世界民族之林。”</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1103/c64036-32272807.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071626529466162349199.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1103/c64036-32272807.html" target="_blank">“如果领导干部都不遵守法律，怎么叫群众遵守法律？”</a></b>
<p>领导干部“递条子”“打招呼”之类的行为已成“雷池”“禁区”。如果还有领导干部仍然习惯于人治思维、迷恋于以权代法，结局只能是习近平告诫的那样——“那十个有十个要栽大跟头”！</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1103/c64036-32272520.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071633568414907361212.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1103/c64036-32272520.html" target="_blank">是种好自家“一亩三分地”，还是大家抱成团朝着顶层设计的目标一起做？</a></b>
<p>十八大以来，以习近平同志为核心的党中央着眼全局，聚焦各区域发展优势和短板，纵横联动东西南北、统筹联通国内国外，下出了一盘气势恢宏的发展大棋局。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1102/c64036-32271491.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071633257372320721101.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1102/c64036-32271491.html" target="_blank">“改革哪有不触动现有职能、权限、利益的？”</a></b>
<p>早在机构改革启动之初，习近平就定下基调：“深化党和国家机构改革是要动奶酪的、是要触动利益的、也是真刀真枪的，是需要拿出自我革新的勇气和胸怀的。”</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1102/c64036-32271489.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071615357495097272073.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1102/c64036-32271489.html" target="_blank">“是简单以国内生产总值增长率论英雄，还是强调以提高经济增长质量和效益为立足点？”</a></b>
<p>习近平总书记给出清晰回答：要坚持正确政绩观，不简单以生产总值增长率论英雄，不要被短期经济指标的波动所左右。</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1101/c64036-32270780.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071620376918156402430.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1101/c64036-32270780.html" target="_blank">“人家把核心技术当‘定海神针’、‘不二法器’，怎么可能提供给你呢？”</a></b>
<p>习近平的决断斩钉截铁：“在日趋激烈的全球综合国力竞争中，我们没有更多选择，非走自主创新道路不可。”</p></span></div>
</div>
<div class="swiper-slide"><a href="http://cpc.people.com.cn/GB/67481/441425/index.html" target=_blank><img src="/img/MAIN/2021/11/121189/images/bt01.png" class="btpic" /></a>
<div class="pic"><a href="http://cpc.people.com.cn/n1/2021/1101/c64036-32270532.html" target=_blank><img src="/NMediaFile/2021/1107/MAIN202111071623565670673726803.jpg" width="580" height="325"/></a><span><b><a href="http://cpc.people.com.cn/n1/2021/1101/c64036-32270532.html" target="_blank">是搞“手榴弹炸跳蚤”，还是对症下药、精准滴灌、靶向治疗？</a></b>
<p>习近平说：“要把不清不楚变成一清二楚”“不搞大水漫灌，不搞手榴弹炸跳蚤，因村因户因人施策，对症下药、精准滴灌、靶向治疗，扶贫扶到点上扶到根上”。</p></span></div>
</div>
</div>
<div class="prev3"></div>
<div class="next3"></div>
</div>
</div>
<div class="w1200 p3con1 mt40 clearfix" >
	<div class="fl clearfix">
		<span class="a1"><a href="http://paper.people.com.cn/rmrb/html/2021-11/12/nbs.D110000renmrb_01.htm" target=_blank><img src="/NMediaFile/2021/1112/MAIN202111120818381013407587992.jpg" width="315" height="450" border="0" alt="11月12日人民日报头条版面"/></a></span>

		<span class="a2 active"><a href="http://paper.people.com.cn/rmrb/html/2021-11/12/nbs.D110000renmrb_03.htm" target=_blank><img src="/NMediaFile/2021/1112/MAIN202111120819423560499506261.jpg" width="315" height="450" border="0" alt="11月12日人民日报3版版面图片"/></a></span>

	</div>
	<div class="fr clearfix">
		<div class="tit2"><a href="http://politics.people.com.cn/GB/8198/441427/index.html" target="_blank">新时代的关键抉择</a></div>
<ul class="list2"><li><a href='/n1/2021/1109/c64387-32277080.html' target=_blank><a href="http://politics.people.com.cn/n1/2021/1109/c1001-32276994.html" target="_blank">以习近平同志为核心的党中央推动构建人类命运共同体述评</a></a></li>
<li><a href='/n1/2021/1108/c64387-32275948.html' target=_blank><a href="http://politics.people.com.cn/n1/2021/1108/c1001-32275860.html" target="_blank">以习近平同志为核心的党中央推进党风廉政建设和反腐败斗争述评</a></a></li>
<li><a href='/n1/2021/1107/c64387-32275466.html' target=_blank><a href="http://politics.people.com.cn/n1/2021/1107/c1001-32275421.html" target="_blank">以习近平同志为核心的党中央推进国防和军队现代化述评</a></a></li>
<li><a href='/n1/2021/1106/c64094-32275134.html' target=_blank><a href="http://politics.people.com.cn/n1/2021/1106/c1001-32275074.html" target="_blank">以习近平同志为核心的党中央推进生态文明建设述评</a></a></li>
<li><a href='/n1/2021/1106/c64094-32275135.html' target=_blank><a href="http://politics.people.com.cn/n1/2021/1105/c1001-32274074.html" target="_blank">以习近平同志为核心的党中央推进区域协调发展述评</a></a></li>
</ul>
		<div class="tit2 mt30"><a href="http://cpc.people.com.cn/GB/67481/441387/index.html" target="_blank">新思想引领新征程·时代答卷</a></div>
<ul class="list2"><li><a href='/n1/2021/1028/c64387-32266673.html' target=_blank>“创新引领率先实现东部地区优化发展”</a></li>
<li><a href='/n1/2021/1027/c64387-32265513.html' target=_blank>“中部地区这个‘脊梁’要更硬一点”</a></li>
<li><a href='/n1/2021/1026/c64387-32264136.html' target=_blank>“东北来得比较多，我十分关心这里的振兴发展”</a></li>
<li><a href='/n1/2021/1025/c64387-32262813.html' target=_blank>“强化举措推进西部大开发形成新格局”</a></li>
<li><a href='/n1/2021/1022/c64387-32260770.html' target=_blank>“积极作为深入推进粤港澳大湾区建设”</a></li>
</ul>
	</div>
</div>
<a id="video" name="video"></a>
<div class="w1200 tit1 clearfix"><img src="/img/MAIN/2021/11/121189/images/titn3.png" /></div>
<div class="w1200 clearfix p4con" >
	<div class="swiper-container-p2 white">
		<div class="swiper-wrapper">
			<div class="swiper-slide"><div class="pic1 fl"><a href="http://cpc.people.com.cn/GB/67481/441273/441480/index.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191419141263060119235.jpg" width="600" height="340"/><span>中共中央就党的十九届六中全会精神举行新闻发布会</span></a></div>

			<div class="pic2 fl">
	<ul class="clearfix"><li><a href="http://cpc.people.com.cn/n1/2021/1118/c64387-32285847.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191423188638878817197.png" width="290" height="165" alt=""/></a><a href="http://cpc.people.com.cn/n1/2021/1118/c64387-32285847.html" target=_blank></a></li>
<li><a href="http://v.people.cn/n1/2021/1110/c61600-32278710.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191436019776258418743.jpg" width="290" height="165" alt=""/></a><a href="http://v.people.cn/n1/2021/1110/c61600-32278710.html" target=_blank></a></li>
<li><a href="http://cpc.people.com.cn/n1/2021/1118/c64387-32285846.html" target=_blank><img src="/NMediaFile/2021/1119/MAIN202111191439120219733396973.png" width="290" height="165" alt=""/></a><a href="http://cpc.people.com.cn/n1/2021/1118/c64387-32285846.html" target=_blank></a></li>
<li><a href="http://politics.people.com.cn/n1/2021/1109/c1001-32277549.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101629172147068377252.png" width="290" height="165" alt=""/></a><a href="http://politics.people.com.cn/n1/2021/1109/c1001-32277549.html" target=_blank></a></li>
</ul>
</div>
</div>
			
			
			
			
			
			
			
			
		</div>
		<div class="swiper-pagination2"></div>
	</div>			
</div>
<a id="fendou" name="fendou"></a>
<div class="w1200 tit1 clearfix"><a href="http://cpc.people.com.cn/GB/67481/435238/index.html" target="_blank"></a><img src="/img/MAIN/2021/11/121189/images/titn4.png" /></div>
<div class="g-text-center"><img src="/img/MAIN/2021/06/121014/images/bg-juanzhou.png" alt=""></div>
<div class="w1200 p5con clearfix" >
	<div class="left-nav">
	  <ul class="list-nav1 white"><li class="active"><span>百年<br>历程</span></li>
<li><span>伟大<br>成就</span></li>
<li><span>历史<br>经验</span></li>
<li><span>理论<br>创新</span></li></ul>
	</div>
	<div class="right-content">
	  <div class="item-content">
<ul class="list-img"><li><h3>深刻领会党百年奋斗的历史经验</h3><a href="http://cpc.people.com.cn/n1/2021/1115/c64387-32281969.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111062053406495421699806.png" class="img-left" width="258" height="182" alt="党的历史是最生动、最有说服力的教科书，我们党历来高度注重总结历史经验。党一步步走过来，很重要的一条就是不断总结经验、提高本领，不断提高应对风险、迎接挑战、化险为夷的能力水平。"/></a><div class="right-desc"><p><a href="http://cpc.people.com.cn/n1/2021/1115/c64387-32281969.html" target=_blank>党的历史是最生动、最有说服力的教科书，我们党历来高度注重总结历史经验。党一步步走过来，很重要的一条就是不断总结经验、提高本领，不断提高应对风险、迎接挑战、化险为夷的能力水平。</a></p></div></li>
<li><h3>深刻把握党百年奋斗的重大成就</h3><a href="http://cpc.people.com.cn/n1/2021/1115/c64387-32282668.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111062059537648157704315.png" class="img-left" width="258" height="182" alt="过去一百年，党向人民、向历史交出了一份优异的答卷。现在，党团结带领中国人民又踏上了实现第二个百年奋斗目标新的赶考之路。"/></a><div class="right-desc"><p><a href="http://cpc.people.com.cn/n1/2021/1115/c64387-32282668.html" target=_blank>过去一百年，党向人民、向历史交出了一份优异的答卷。现在，党团结带领中国人民又踏上了实现第二个百年奋斗目标新的赶考之路。</a></p></div></li>
</ul>
	  <ul class="list-news"><li><div><a href='/n1/2021/1114/c64036-32281615.html' target=_blank>深刻理解党百年奋斗的历史意义</a></div></li>
<li><div><a href='/n1/2021/1115/c64387-32281970.html' target=_blank>以更加昂扬的姿态迈向新征程建功新时代</a></div></li>
<li><div><a href='/n1/2021/1115/c64387-32282669.html' target=_blank>百年奋斗书写中华民族最恢宏的史诗</a></div></li>
<li><div><a href='/n1/2021/1115/c64387-32282670.html' target=_blank>马克思主义中国化新的飞跃</a></div></li>
<li><div><a href="http://cpc.people.com.cn/n1/2021/0416/c64387-32079597.html" target="_blank">人民对美好生活的向往就是我们的奋斗目标</a></div></li></ul>
</div>
	  <div class="item-content">
<ul class="list-img"><li><h3>团结更多的人共同前进</h3><a href="http://cpc.people.com.cn/n1/2021/1115/c64387-32281983.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111062110496478367530944.jpg" class="img-left" width="258" height="182" alt="构建人类命运共同体理念倡导坚持多边主义，呼吁国际社会加强团结合作，共建美好地球家园。在国际社会携手应对全球性挑战的过程中，构建人类命运共同体理念更加深入人心。"/></a><div class="right-desc"><p><a href="http://cpc.people.com.cn/n1/2021/1115/c64387-32281983.html" target=_blank>构建人类命运共同体理念倡导坚持多边主义，呼吁国际社会加强团结合作，共建美好地球家园。在国际社会携手应对全球性挑战的过程中，构建人类命运共同体理念更加深入人心。</a></p></div></li>
<li><h3>为全球减贫事业注入信心和力量</h3><a href="http://cpc.people.com.cn/n1/2021/1115/c64387-32282036.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111062119075266286922681.png" class="img-left" width="258" height="182" alt="中国在取得脱贫攻坚战全面胜利的同时，积极同各方分享减贫经验，在联合国框架下强化南南合作，共同落实联合国2030年可持续发展议程，为全球减贫事业注入信心和力量。&#13;&#13;"/></a><div class="right-desc"><p><a href="http://cpc.people.com.cn/n1/2021/1115/c64387-32282036.html" target=_blank>中国在取得脱贫攻坚战全面胜利的同时，积极同各方分享减贫经验，在联合国框架下强化南南合作，共同落实联合国2030年可持续发展议程，为全球减贫事业注入信心和力量。

</a></p></div></li>
</ul>
	  <ul class="list-news"><li><div><a href='/n1/2021/1113/c64093-32281289.html' target=_blank>“共同促进包容可持续发展”</a></div></li>
<li><div><a href='/n1/2021/1114/c64387-32281625.html' target=_blank>“中国为应对气候变化作出积极贡献”</a></div></li>
<li><div><a href='/n1/2021/1115/c64387-32281984.html' target=_blank>“中国在亚太区域经济合作中发挥重要作用”</a></div></li>
<li><div><a href='/n1/2021/1115/c64387-32281985.html' target=_blank>“我们对在中国的长远发展充满信心”</a></div></li>
<li><div><a href="http://finance.people.com.cn/n1/2021/1106/c1004-32275362.html" target="_blank">中国加入世界贸易组织20年与世界共赢</a></div></li></ul>
</div>
	  <div class="item-content">
<ul class="list-img"><li><h3>全过程人民民主是一个完整的制度链条</h3><a href="http://cpc.people.com.cn/n1/2021/1112/c64387-32280809.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111062133498826541907135.png" class="img-left" width="258" height="182" alt="中国人民有着高度的政治制度自信，根本原因就在于我国全过程人民民主是民主含量高、民主成色足、深受中国人民欢迎的民主，这才是真正的人民民主。"/></a><div class="right-desc"><p><a href="http://cpc.people.com.cn/n1/2021/1112/c64387-32280809.html" target=_blank>中国人民有着高度的政治制度自信，根本原因就在于我国全过程人民民主是民主含量高、民主成色足、深受中国人民欢迎的民主，这才是真正的人民民主。</a></p></div></li>
<li><h3>中国创造经济奇迹的“秘诀”</h3><a href="http://cpc.people.com.cn/n1/2021/1112/c64387-32280830.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111062136435392199010867.jpg" class="img-left" width="258" height="182" alt="建立社会主义市场经济体制，实现社会主义与市场经济有机结合，这是我们党的一个伟大创举。改革破除了过去僵化的计划经济体制的束缚，中国经济变成了一池活水，极大地解放和发展了社会生产力。"/></a><div class="right-desc"><p><a href="http://cpc.people.com.cn/n1/2021/1112/c64387-32280830.html" target=_blank>建立社会主义市场经济体制，实现社会主义与市场经济有机结合，这是我们党的一个伟大创举。改革破除了过去僵化的计划经济体制的束缚，中国经济变成了一池活水，极大地解放和发展了社会生产力。</a></p></div></li>
</ul>
	  <ul class="list-news"><li><div><a href='/n1/2021/1112/c64387-32280774.html' target=_blank>“两个确立”是时代呼唤、历史选择、民心所向</a></div></li>
<li><div><a href='/n1/2021/1112/c64387-32280822.html' target=_blank>从两个“立足于”理解《决议》对历史经验的总结</a></div></li>
<li><div><a href='/n1/2021/1112/c64387-32280800.html' target=_blank>共同富裕没有捷径，必须靠艰苦奋斗来实现</a></div></li>
<li><div><a href='/n1/2021/1112/c64387-32280802.html' target=_blank>新时代文化建设的成就主要包括五个方面</a></div></li>
<li><div><a href="http://theory.people.com.cn/n1/2021/1102/c40531-32270964.html" target="_blank">在敢于斗争中争取更大胜利</a></div></li></ul>
</div>
	  <div class="item-content">
<ul class="list-img"><li><h3>中国共产党历史上新的里程碑</h3><a href="http://theory.people.com.cn/n1/2021/1115/c40531-32282073.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111062200011712956213673.png" class="img-left" width="258" height="182" alt="中共十九届六中全会审议通过中国共产党历史上第三个历史决议，对推动全党进一步统一思想、统一意志、统一行动，团结带领全国各族人民夺取新时代中国特色社会主义新的伟大胜利，具有重大现实意义和深远历史意义。"/></a><div class="right-desc"><p><a href="http://theory.people.com.cn/n1/2021/1115/c40531-32282073.html" target=_blank>中共十九届六中全会审议通过中国共产党历史上第三个历史决议，对推动全党进一步统一思想、统一意志、统一行动，团结带领全国各族人民夺取新时代中国特色社会主义新的伟大胜利，具有重大现实意义和深远历史意义。</a></p></div></li>
<li><h3>中华民族历史上最恢宏的史诗</h3><a href="http://theory.people.com.cn/n1/2021/1115/c40531-32282059.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111062202350623515448780.png" class="img-left" width="258" height="182" alt="走得再远，都不能忘记来时的路。过去的成功，不是轻轻松松、敲锣打鼓实现的。勿忘昨天的苦难辉煌，无愧今天的使命担当，不负明天的伟大梦想。"/></a><div class="right-desc"><p><a href="http://theory.people.com.cn/n1/2021/1115/c40531-32282059.html" target=_blank>走得再远，都不能忘记来时的路。过去的成功，不是轻轻松松、敲锣打鼓实现的。勿忘昨天的苦难辉煌，无愧今天的使命担当，不负明天的伟大梦想。</a></p></div></li>
</ul>
	  <ul class="list-news"><li><div><a href='http://theory.people.com.cn/n1/2021/1115/c40531-32282150.html' target=_blank>彰显百年大党的坚定自信和使命担当</a></div></li>
<li><div><a href='http://theory.people.com.cn/n1/2021/1115/c40531-32282170.html' target=_blank>价值与文明：中国共产党的百年探索</a></div></li>
<li><div><a href='http://theory.people.com.cn/n1/2021/1115/c40531-32282353.html' target=_blank>深刻理解中国共产党百年奋斗历史的鲜明主题</a></div></li>
<li><div><a href='http://theory.people.com.cn/n1/2021/1115/c40531-32282371.html' target=_blank>坚定对中国化马克思主义的理论自信</a></div></li>
<li><div><a href='http://theory.people.com.cn/n1/2021/1115/c40531-32282435.html' target=_blank>党的十九届六中全会的重大意义</a></div></li>
</ul>
</div>
	</div>
</div>
<div class="w1200 p7con clearfix" style="display:none;">
	<div class="tit4"><img src="/img/MAIN/2021/11/121189/images/titn1.png" /></div>
	<div class="p7_fr">		
		<div class="pic5"><a href="http://theory.people.com.cn/GB/40557/430713/index.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101603076883995094070.png" width="771" height="301" alt="云讲堂：百年历程中的伟大精神"/></a>
</div>
		<div class="prev5"></div>
		<div class="next5"></div>
		<div class="swiper-container-p5">
			<div class="swiper-wrapper"><div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/0622/c40531-32137379.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101618265366435743787.jpg" width="249" height="420" alt=""/></a></div>
<div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/0708/c40531-32152182.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101618268862943413003.jpg" width="249" height="420" alt=""/></a></div>
<div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/0720/c40531-32163128.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101609524358973180305.jpg" width="249" height="420" alt=""/></a></div>
<div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/0624/c40531-32139717.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101618272438371225722.jpg" width="249" height="420" alt=""/></a></div>
<div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/0706/c40531-32149870.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101609520887219965100.jpg" width="249" height="420" alt=""/></a></div>
<div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/0713/c40531-32156131.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101609527875476976298.jpg" width="249" height="420" alt=""/></a></div>
<div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/0723/c40531-32167411.html" target=_blank><img src="/NMediaFile/2021/1110/MAIN202111101626369416354839239.jpg" width="249" height="420" alt=""/></a></div>
</div>
		</div>
	</div>
</div>
<style type="text/css">
.bk-zgjs{margin-bottom:50px;}
.bk-zgjs .swiper-container{height:100%;overflow: hidden;position:relative;}
.bk-zgjs .content-wrap{position:relative;height:570px;background:#a72e28;border:8px solid #dd6252;}
.bk-zgjs .content-wrap .arrowtop-js{position:absolute;left:120px;top:20px;cursor:pointer;}
.bk-zgjs .content-wrap .arrowbottom-js{position:absolute;left:120px;bottom:10px;cursor:pointer;}
.bk-zgjs .left-nav{position:absolute;left:18px;top:60px;width:223px;height:456px;overflow:hidden;}
.bk-zgjs .left-nav .btn-js{width:218px;text-align:center;color:#933c2f;background:url(/img/MAIN/2021/06/121014/images/bg-btn.png) #decfa4;font: normal 30px/53px "Microsoft YaHei";-webkit-border-radius:4px;border-radius:4px;-webkit-box-shadow:4px 9px 3px 0px #5e261d;box-shadow: 4px 9px 3px 0px #5e261d;cursor: pointer;}
.bk-zgjs .left-nav .btn-js:hover{opacity:0.8;}
.bk-zgjs .right-contents{margin-left:282px;}
.bk-zgjs .right-contents .item-content{display:none;position:relative;padding-top:28px;}
.bk-zgjs .right-contents .item-content:first-child{display: block;}
.bk-zgjs .right-contents .item-content .right-desc-wrap{position:absolute;left:471px;top:39px;width:416px;height:233px;overflow:auto;
color:#fff;}
.bk-zgjs .right-contents .item-content .right-desc-wrap h3{font:bold 20px/1.5 "Microsoft YaHei";margin-bottom:10px;}
.bk-zgjs .right-contents .item-content .right-desc-wrap p{font:normal 18px/2 "Microsoft YaHei";text-indent:2em;}
.bk-zgjs .right-contents .item-content .right-desc-wrap .btn-wrap{text-align:right;}
.bk-zgjs .right-contents .item-content .right-desc-wrap .btn-wrap .detail,.bk-zgjs .right-contents .item-content .right-desc-wrap .btn-wrap a{color:#ede3b4;font-size:16px;}
.bk-zgjs .right-contents .top button{display:none;}
.bk-zgjs .right-contents .top .links-wrap{font-size:0;}
.bk-zgjs .right-contents .top .links-wrap ul{height:226px;background:#4e3e39;font:normal 20px "Microsoft YaHei";color:#fff; padding-top:17px;}
.bk-zgjs .right-contents .top .links-wrap ul li{position:relative;height:63px;line-height:63px;padding-left:18px;white-space:nowrap;  overflow:hidden;text-overflow:ellipsis;}
.bk-zgjs .right-contents .top .links-wrap ul li:hover{color:#3c312a;background: url(/img/MAIN/2021/06/121014/images/bg-li-jingshen.png) left center no-repeat;}
.bk-zgjs .right-contents .top .links-wrap ul li:after{position:absolute;left:20px;bottom:0;display:block;content:"";width:370px;border-bottom: 1px solid #938986;}
.bk-zgjs .right-contents .top .links-wrap ul li:last-child:after{display: none;}
.bk-zgjs .right-contents .top .links-wrap .left-links{display:inline-block;width:444px;vertical-align:top;margin-right:4px;}
.bk-zgjs .right-contents .top .links-wrap .right-links{width:460px;display:inline-block;vertical-align:top;}
.bk-zgjs .right-contents .top:before{content:"";position:absolute;left:-28px;top:44px;width:30px;height:37px;background:url(/img/MAIN/2021/11/121189/images/jiao1.png) no-repeat;}
.bk-zgjs .right-contents .top .desc{position:absolute;left:0;top:272px;width:908px;height:226px;}
.bk-zgjs .right-contents .top .desc .desc-tit{display:none;}
.bk-zgjs .right-contents .img-left{position:absolute;left:12px;top:12px;}
.bk-zgjs .right-contents .links-wrap{font-size:0;margin-top:10px;}
.bk-zgjs .right-contents .links-wrap ul{height:226px;background:#bf443e;font:normal 20px "Microsoft YaHei";color:#fff;padding-top: 17px;}
.bk-zgjs .right-contents .links-wrap ul li{position:relative;height:63px;line-height:63px;padding-left:18px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.bk-zgjs .right-contents .links-wrap ul li a:link{color:#fff;}
.bk-zgjs .right-contents .links-wrap ul li:hover{color:#3c312a;background:url(/img/MAIN/2021/06/121014/images/bg-li-jingshen.png) left center no-repeat;}
.bk-zgjs .right-contents .top .links-wrap ul li:after{position:absolute;left:20px;bottom:0;display:block;content:"";width:370px;      border-bottom:1px solid #938986;}
.bk-zgjs .right-contents .links-wrap ul li:last-child:after{display:none;}
.bk-zgjs .right-contents .links-wrap .left-links{display:inline-block;width:444px;vertical-align:top;margin-right:4px;}
.bk-zgjs .right-contents .links-wrap .right-links{width:448px;display:inline-block;vertical-align:top;}
.bk-zgjs .right-contents .top{position:relative;width:895px;height:264px;background:#930c0d;}
</style>
<div class="bk bk-zgjs w1200 clearfix" >
  <div class="w1200 tit1 clearfix"><img src="/img/MAIN/2021/11/121189/images/titn6.png" /></div>
  <div class="content-wrap">
    <!-- 自动生成 -->
    <div class="left-nav">
      <div class="swiper-container swiper-container-js">
        <div class="swiper-wrapper">
          <div class="swiper-slide">
            <!-- <div class="btn-js">红船精神1</div> -->
          </div>
        </div>
      </div>
    </div>
    <img src="/img/MAIN/2021/06/121014/images/arrowtop-jingshen.png" alt="" class="arrowtop-js">
    <img src="/img/MAIN/2021/06/121014/images/arrow-bottom-jingshen.png" alt="" class="arrowbottom-js">
    <div class="right-contents">
      <div>
        <!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">精神谱系</h3><a href="http://theory.people.com.cn/GB/40557/430713/index.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101710491096229001035.png" class="img-left" width="435" height="240" alt="第一批纳入中国共产党人精神谱系的伟大精神是：建党精神；井冈山精神、苏区精神、长征精神、遵义会议精神、延安精神、抗战精神、红岩精神、西柏坡精神、照金精神、东北抗联精神、南泥湾精神、太行精神（吕梁精神）、大别山精神、沂蒙精神、老区精神、张思德精神；抗美援朝精神、“两弹一星”精神、雷锋精神、焦裕禄精神、大庆精神（铁人精神）、红旗渠精神、北大荒精神、塞罕坝精神、“两路”精神、老西藏精神（孔繁森精神）、西迁精神、王杰精神；改革开放精神、特区精神、抗洪精神、抗击“非典”精神、抗震救灾精神、载人航天精神、劳模精神（劳动精神、工匠精神）、青藏铁路精神、女排精神；脱贫攻坚精神、抗疫精神、“三牛”精神、科学家精神、企业家精神、探月精神、新时代北斗精神、丝路精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p><div style="text-align: left;"><span style="font-size: small;">第一批纳入中国共产党人精神谱系的伟大精神是：</span></div><div style="text-align: left;"><span style="font-size: small;">建党精神；</span></div><div style="text-align: left;"><font size="2">井冈山精神、苏区精神、长征精神、遵义会议精神、延安精神、抗战精神、红岩精神、西柏坡精神、照金精神、东北抗联精神、南泥湾精神、太行精神（吕梁精神）、大别山精神、沂蒙精神、老区精神、张思德精神；</font></div><div style="text-align: left;"><font size="2">抗美援朝精神、“两弹一星”精神、雷锋精神、焦裕禄精神、大庆精神（铁人精神）、红旗渠精神、北大荒精神、塞罕坝精神、“两路”精神、老西藏精神（孔繁森精神）、西迁精神、王杰精神；改革开放精神、特区精神、抗洪精神、抗击“非典”精神、抗震救灾精神、载人航天精神、劳模精神（劳动精神、工匠精神）、青藏铁路精神、女排精神；</font></div><div style="text-align: left;"><font size="2">脱贫攻坚精神、抗疫精神、“三牛”精神、科学家精神、企业家精神、探月精神、新时代北斗精神、丝路精神。</font></div></p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">新时代北斗精神</h3><a href="http://cpc.people.com.cn/n1/2021/1214/c64387-32307105.html" target="_blank"><img src="/NMediaFile/2021/1216/MAIN202112160926366275604335464.png" class="img-left" width="435" height="240" alt="如同北斗指路，新时代北斗精神将持续伴随着中国航天人奔赴星辰大海、勇攀科技高峰。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>如同北斗指路，新时代北斗精神将持续伴随着中国航天人奔赴星辰大海、勇攀科技高峰。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">探月精神</h3><a href="http://cpc.people.com.cn/n1/2021/1208/c64387-32302134.html" target="_blank"><img src="/NMediaFile/2021/1208/MAIN202112080836129097218354817.jpg" class="img-left" width="435" height="240" alt="从嫦娥一号实现我国月球探测“零的突破”，到嫦娥五号月球采样返回，我国探月工程不仅开启了人类月球探测新篇章，书写了中国的探月传奇，也在实践中凝练了“追逐梦想、勇于探索、协同攻坚、合作共赢”的探月精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>从嫦娥一号实现我国月球探测“零的突破”，到嫦娥五号月球采样返回，我国探月工程不仅开启了人类月球探测新篇章，书写了中国的探月传奇，也在实践中凝练了“追逐梦想、勇于探索、协同攻坚、合作共赢”的探月精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">企业家精神</h3><a href="http://cpc.people.com.cn/n1/2021/1206/c64387-32300132.html" target="_blank"><img src="/NMediaFile/2021/1208/MAIN202112080834000277073342779.jpg" class="img-left" width="435" height="240" alt="广大企业家主动为国担当、为国分忧，顺应时代发展，勇于拼搏进取，为积累社会财富、创造就业岗位、促进经济社会发展、增强综合国力作出了重要贡献，在波澜壮阔的历史画卷中书写下企业家精神的华彩篇章。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>广大企业家主动为国担当、为国分忧，顺应时代发展，勇于拼搏进取，为积累社会财富、创造就业岗位、促进经济社会发展、增强综合国力作出了重要贡献，在波澜壮阔的历史画卷中书写下企业家精神的华彩篇章。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">“三牛”精神</h3><a href="http://cpc.people.com.cn/n1/2021/1204/c64387-32299379.html" target="_blank"><img src="/NMediaFile/2021/1208/MAIN202112080831072241084128740.jpg" class="img-left" width="435" height="240" alt="“三牛”精神传承着中华民族生生不息、长盛不衰的强大基因，揭示了中国共产党和中国人民自强不息、砥砺奋进的精神密码，这既是对过去中国人民不畏艰险、锐意进取的深刻总结，也是对未来中国人民攻坚克难、开拓前行的深情寄望。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>“三牛”精神传承着中华民族生生不息、长盛不衰的强大基因，揭示了中国共产党和中国人民自强不息、砥砺奋进的精神密码，这既是对过去中国人民不畏艰险、锐意进取的深刻总结，也是对未来中国人民攻坚克难、开拓前行的深情寄望。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">青藏铁路精神</h3><a href="http://cpc.people.com.cn/n1/2021/1130/c64387-32295012.html" target="_blank"><img src="/NMediaFile/2021/1130/MAIN202111301531105703711038057.jpg" class="img-left" width="435" height="240" alt="忆往昔，10多万建设大军冒严寒、顶风雪、战缺氧，攻克了“高寒缺氧、多年冻土、生态脆弱”三大世界性难题，建成了世界上海拔最高、线路最长的高原铁路，铸就了“挑战极限、勇创一流”的青藏铁路精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>忆往昔，10多万建设大军冒严寒、顶风雪、战缺氧，攻克了“高寒缺氧、多年冻土、生态脆弱”三大世界性难题，建成了世界上海拔最高、线路最长的高原铁路，铸就了“挑战极限、勇创一流”的青藏铁路精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">改革开放精神</h3><a href="http://cpc.people.com.cn/n1/2021/1129/c64387-32293956.html" target="_blank"><img src="/NMediaFile/2021/1129/MAIN202111291016341451778876667.jpg" class="img-left" width="435" height="240" alt="沿着改革开放这条“必由之路”，我们党带领人民以一往无前的进取精神和波澜壮阔的创新实践，让改革开放的大潮在神州大地奏响激扬乐章。伟大的改革开放精神跨越时空、历久弥新，成为中国共产党人精神谱系的重要组成部分。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>沿着改革开放这条“必由之路”，我们党带领人民以一往无前的进取精神和波澜壮阔的创新实践，让改革开放的大潮在神州大地奏响激扬乐章。伟大的改革开放精神跨越时空、历久弥新，成为中国共产党人精神谱系的重要组成部分。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">王杰精神</h3><a href="http://theory.people.com.cn/n1/2021/1129/c40531-32293937.html" target="_blank"><img src="/NMediaFile/2021/1129/MAIN202111290856100121709514289.png" class="img-left" width="435" height="240" alt="王杰精神过去是、现在是、将来永远是我们的宝贵精神财富，要学习践行王杰精神，让王杰精神绽放新的时代光芒。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>王杰精神过去是、现在是、将来永远是我们的宝贵精神财富，要学习践行王杰精神，让王杰精神绽放新的时代光芒。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">西迁精神</h3><a href="http://cpc.people.com.cn/n1/2021/1124/c64387-32290276.html" target="_blank"><img src="/NMediaFile/2021/1124/MAIN202111240911191162056364680.jpg" class="img-left" width="435" height="240" alt="“西迁精神”的核心是爱国主义，精髓是听党指挥跟党走，与党和国家、与民族和人民同呼吸、共命运，具有深刻现实意义和历史意义。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>“西迁精神”的核心是爱国主义，精髓是听党指挥跟党走，与党和国家、与民族和人民同呼吸、共命运，具有深刻现实意义和历史意义。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">老西藏精神</h3><a href="http://cpc.people.com.cn/n1/2021/1123/c64387-32289293.html" target="_blank"><img src="/NMediaFile/2021/1123/MAIN202111230936474337305143407.png" class="img-left" width="435" height="240" alt="今年是西藏和平解放70周年。1951年5月23日，西藏宣告和平解放，古老的雪域高原从此换了人间，从落后走向进步、从专制走向民主、从贫穷走向富裕、从封闭走向开放、从黑暗走向光明。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>今年是西藏和平解放70周年。1951年5月23日，西藏宣告和平解放，古老的雪域高原从此换了人间，从落后走向进步、从专制走向民主、从贫穷走向富裕、从封闭走向开放、从黑暗走向光明。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">“两路”精神</h3><a href="http://cpc.people.com.cn/n1/2021/1122/c64387-32288105.html" target="_blank"><img src="/NMediaFile/2021/1122/MAIN202111221019383356329845491.png" class="img-left" width="435" height="240" alt="“60年来，在建设和养护公路的过程中，形成和发扬了一不怕苦、二不怕死，顽强拼搏、甘当路石，军民一家、民族团结的‘两路’精神。”2014年，习近平总书记就川藏、青藏公路通车60周年作出重要批示，要求进一步弘扬“两路”精神，助推西藏发展。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>“60年来，在建设和养护公路的过程中，形成和发扬了一不怕苦、二不怕死，顽强拼搏、甘当路石，军民一家、民族团结的‘两路’精神。”2014年，习近平总书记就川藏、青藏公路通车60周年作出重要批示，要求进一步弘扬“两路”精神，助推西藏发展。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">塞罕坝精神</h3><a href="http://cpc.people.com.cn/n1/2021/1116/c64387-32283126.html" target="_blank"><img src="/NMediaFile/2021/1116/MAIN202111160921531834943267774.jpg" class="img-left" width="435" height="240" alt="弘扬塞罕坝精神，中华大地山越来越绿、水越来越清。经过多年持续努力，我国森林覆盖率达到23.04%，森林面积和蓄积量连续30多年保持“双增长”，成为全球增林扩绿最多最快的国家。良好生态环境，厚植了全面建成小康社会的绿色底色和质量成色。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>弘扬塞罕坝精神，中华大地山越来越绿、水越来越清。经过多年持续努力，我国森林覆盖率达到23.04%，森林面积和蓄积量连续30多年保持“双增长”，成为全球增林扩绿最多最快的国家。良好生态环境，厚植了全面建成小康社会的绿色底色和质量成色。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">北大荒精神</h3><a href="http://cpc.people.com.cn/n1/2021/1115/c64387-32281963.html" target="_blank"><img src="/NMediaFile/2021/1115/MAIN202111150834497051439308048.jpg" class="img-left" width="435" height="240" alt="从亘古荒原到“中华大粮仓”，几代农垦人战天斗地，锻造出“艰苦奋斗、勇于开拓、顾全大局、无私奉献”的北大荒精神。如今的北大荒，黑土地生机勃勃，大型联合收割机隆隆轰鸣，迎接着一个又一个丰收年景。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>从亘古荒原到“中华大粮仓”，几代农垦人战天斗地，锻造出“艰苦奋斗、勇于开拓、顾全大局、无私奉献”的北大荒精神。如今的北大荒，黑土地生机勃勃，大型联合收割机隆隆轰鸣，迎接着一个又一个丰收年景。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">红旗渠精神</h3><a href="http://cpc.people.com.cn/n1/2021/1111/c64387-32279120.html" target="_blank"><img src="/NMediaFile/2021/1111/MAIN202111110823005890059084072.jpg" class="img-left" width="435" height="240" alt="在中国共产党领导下，林县人民自力更生、艰苦创业、团结协作、无私奉献，靠着“一锤、一钎、一双手”，创造出太行山上的人间奇迹，培育了伟大的红旗渠精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>在中国共产党领导下，林县人民自力更生、艰苦创业、团结协作、无私奉献，靠着“一锤、一钎、一双手”，创造出太行山上的人间奇迹，培育了伟大的红旗渠精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">张思德精神</h3><a href="http://cpc.people.com.cn/n1/2021/1110/c64387-32278122.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111100858489844783048888.jpg" class="img-left" width="435" height="240" alt="全心全意为人民服务是党的根本宗旨。延安时期，毛泽东同志在追悼张思德同志时发表的《为人民服务》的演讲，深刻揭示了党群关系、干群关系、军民关系的真谛。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>全心全意为人民服务是党的根本宗旨。延安时期，毛泽东同志在追悼张思德同志时发表的《为人民服务》的演讲，深刻揭示了党群关系、干群关系、军民关系的真谛。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">老区精神 </h3><a href="http://cpc.people.com.cn/n1/2021/1109/c64387-32277062.html" target="_blank"><img src="/NMediaFile/2021/1109/MAIN202111091114141196830115830.png" class="img-left" width="435" height="240" alt="老区和老区人民，为我们党领导的中国革命作出了重大牺牲和贡献。这些牺牲和贡献永远镌刻在中国共产党、中国人民解放军、中华人民共和国的历史丰碑上。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>老区和老区人民，为我们党领导的中国革命作出了重大牺牲和贡献。这些牺牲和贡献永远镌刻在中国共产党、中国人民解放军、中华人民共和国的历史丰碑上。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">沂蒙精神</h3><a href="http://cpc.people.com.cn/n1/2021/1104/c64387-32272976.html" target="_blank"><img src="/NMediaFile/2021/1104/MAIN202111041017126699536332651.png" class="img-left" width="435" height="240" alt="沂蒙精神与延安精神、井冈山精神、西柏坡精神一样，是党和国家的宝贵精神财富，要不断结合新的时代条件发扬光大。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>沂蒙精神与延安精神、井冈山精神、西柏坡精神一样，是党和国家的宝贵精神财富，要不断结合新的时代条件发扬光大。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">大别山精神</h3><a href="http://cpc.people.com.cn/n1/2021/1103/c64387-32271921.html" target="_blank"><img src="/NMediaFile/2021/1103/MAIN202111030915411006994847601.png" class="img-left" width="435" height="240" alt="2019年9月，习近平总书记在河南考察时强调，“鄂豫皖苏区根据地是我们党的重要建党基地，焦裕禄精神、红旗渠精神、大别山精神等都是我们党的宝贵精神财富”，勉励广大党员、干部“在接受红色教育中守初心、担使命，把革命先烈为之奋斗、为之牺牲的伟大事业奋力推向前进”。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>2019年9月，习近平总书记在河南考察时强调，“鄂豫皖苏区根据地是我们党的重要建党基地，焦裕禄精神、红旗渠精神、大别山精神等都是我们党的宝贵精神财富”，勉励广大党员、干部“在接受红色教育中守初心、担使命，把革命先烈为之奋斗、为之牺牲的伟大事业奋力推向前进”。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">太行、吕梁精神</h3><a href="http://cpc.people.com.cn/n1/2021/1101/c64387-32269792.html" target="_blank"><img src="/NMediaFile/2021/1101/MAIN202111011019099447534879771.jpg" class="img-left" width="435" height="240" alt="山西也是具有光荣革命传统的地方，是八路军总部所在地，是抗日战争主战场之一，建立了晋绥、晋察冀、晋冀鲁豫抗日根据地，平型关大捷、百团大战等闻名中外，太行精神、吕梁精神是我们党宝贵的精神财富。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>山西也是具有光荣革命传统的地方，是八路军总部所在地，是抗日战争主战场之一，建立了晋绥、晋察冀、晋冀鲁豫抗日根据地，平型关大捷、百团大战等闻名中外，太行精神、吕梁精神是我们党宝贵的精神财富。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">南泥湾精神</h3><a href="http://cpc.people.com.cn/n1/2021/1029/c64387-32267909.html" target="_blank"><img src="/NMediaFile/2021/1029/MAIN202110290949115117117542183.jpg" class="img-left" width="435" height="240" alt="作为中国共产党人精神谱系的重要组成部分，南泥湾精神成为鼓舞和激励全党全国各族人民风雨无阻、勇敢前进的强大精神动力。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>作为中国共产党人精神谱系的重要组成部分，南泥湾精神成为鼓舞和激励全党全国各族人民风雨无阻、勇敢前进的强大精神动力。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">东北抗联精神</h3><a href="http://cpc.people.com.cn/n1/2021/1028/c64387-32266660.html" target="_blank"><img src="/NMediaFile/2021/1028/MAIN202110281100341286094560586.jpg" class="img-left" width="435" height="240" alt="在艰苦卓绝的抗日战争中，中华儿女为国家生存而战、为民族复兴而战、为人类正义而战，社会动员之广泛，民族觉醒之深刻，战斗意志之顽强，必胜信念之坚定，都达到了空前的高度。白山黑水间，茫茫林海中，东北抗日联军在中国共产党领导下，长期与凶恶敌人斗争，用鲜血和生命谱写了壮丽篇章。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>在艰苦卓绝的抗日战争中，中华儿女为国家生存而战、为民族复兴而战、为人类正义而战，社会动员之广泛，民族觉醒之深刻，战斗意志之顽强，必胜信念之坚定，都达到了空前的高度。白山黑水间，茫茫林海中，东北抗日联军在中国共产党领导下，长期与凶恶敌人斗争，用鲜血和生命谱写了壮丽篇章。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">照金精神</h3><a href="http://cpc.people.com.cn/n1/2021/1027/c64387-32265259.html" target="_blank"><img src="/NMediaFile/2021/1027/MAIN202110271013567232133827097.jpg" class="img-left" width="435" height="240" alt="革命先辈以不怕牺牲、顽强拼搏的英雄气概，独立自主、开拓进取的创新勇气，从实际出发、密切联系群众的工作作风，开展了艰苦卓绝的革命斗争实践，孕育形成了伟大的照金精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>革命先辈以不怕牺牲、顽强拼搏的英雄气概，独立自主、开拓进取的创新勇气，从实际出发、密切联系群众的工作作风，开展了艰苦卓绝的革命斗争实践，孕育形成了伟大的照金精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">西柏坡精神</h3><a href="http://cpc.people.com.cn/n1/2021/1022/c64387-32260766.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101749138666312737710.jpg" class="img-left" width="435" height="240" alt="诞生于战火硝烟中的西柏坡精神永远是激励我们奋勇前进、争取胜利的强大动力。始终牢记“两个务必”，永远保持同人民群众的血肉联系，我们党就一定能团结带领亿万人民走好新时代的长征路，在新时代的赶考路上不断交出优异答卷。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>诞生于战火硝烟中的西柏坡精神永远是激励我们奋勇前进、争取胜利的强大动力。始终牢记“两个务必”，永远保持同人民群众的血肉联系，我们党就一定能团结带领亿万人民走好新时代的长征路，在新时代的赶考路上不断交出优异答卷。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">红岩精神</h3><a href="http://cpc.people.com.cn/n1/2021/1021/c64387-32259610.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101755143585633547353.jpg" class="img-left" width="435" height="240" alt="崇高的思想境界，是红岩精神的本质属性，体现了共产党人坚忍不拔的革命意志、坚守不移的民族大义、海纳百川的宽广胸怀。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>崇高的思想境界，是红岩精神的本质属性，体现了共产党人坚忍不拔的革命意志、坚守不移的民族大义、海纳百川的宽广胸怀。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">遵义会议精神</h3><a href="http://cpc.people.com.cn/n1/2021/1019/c64387-32257371.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101759400522527713176.jpg" class="img-left" width="435" height="240" alt="如今的贵州，处处呈现欣欣向荣的景象。遵义会议精神始终激励着贵州各族群众坚守初心使命，努力开创百姓富、生态美的多彩贵州新未来。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>如今的贵州，处处呈现欣欣向荣的景象。遵义会议精神始终激励着贵州各族群众坚守初心使命，努力开创百姓富、生态美的多彩贵州新未来。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">脱贫攻坚精神</h3><a href="http://cpc.people.com.cn/n1/2021/1018/c64387-32256231.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101804455743038316856.jpg" class="img-left" width="435" height="240" alt="脱贫攻坚伟大斗争，锻造形成了“上下同心、尽锐出战、精准务实、开拓创新、攻坚克难、不负人民”的脱贫攻坚精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>脱贫攻坚伟大斗争，锻造形成了“上下同心、尽锐出战、精准务实、开拓创新、攻坚克难、不负人民”的脱贫攻坚精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">伟大抗疫精神</h3><a href="http://cpc.people.com.cn/n1/2021/1014/c64387-32253014.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101800286196416390972.jpg" class="img-left" width="435" height="240" alt="同严重疫情的殊死较量中，中国人民和中华民族以敢于斗争、敢于胜利的大无畏气概，铸就了生命至上、举国同心、舍生忘死、尊重科学、命运与共的伟大抗疫精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>同严重疫情的殊死较量中，中国人民和中华民族以敢于斗争、敢于胜利的大无畏气概，铸就了生命至上、举国同心、舍生忘死、尊重科学、命运与共的伟大抗疫精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">科学家精神</h3><a href="http://cpc.people.com.cn/n1/2021/1012/c64387-32250407.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101757254707719383407.png" class="img-left" width="435" height="240" alt="科学成就离不开精神支撑。科学家精神是科技工作者在长期科学实践中积累的宝贵精神财富。新中国成立以来，广大科技工作者在祖国大地上树立起一座座科技创新的丰碑，也铸就了独特的精神气质。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>科学成就离不开精神支撑。科学家精神是科技工作者在长期科学实践中积累的宝贵精神财富。新中国成立以来，广大科技工作者在祖国大地上树立起一座座科技创新的丰碑，也铸就了独特的精神气质。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">工匠精神</h3><a href="http://cpc.people.com.cn/n1/2021/1011/c64387-32249231.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101754480889802097176.png" class="img-left" width="435" height="240" alt="在中国共产党领导的血与火的革命中、如火如荼的建设中、意气风发的改革中，涌现出了一大批辛勤付出、无私奉献甚至不畏牺牲的工匠，促使具有无产阶级和社会主义性质的工匠精神应运而生。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>在中国共产党领导的血与火的革命中、如火如荼的建设中、意气风发的改革中，涌现出了一大批辛勤付出、无私奉献甚至不畏牺牲的工匠，促使具有无产阶级和社会主义性质的工匠精神应运而生。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">劳动精神</h3><a href="http://cpc.people.com.cn/n1/2021/1003/c64093-32245223.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101752253762743446865.png" class="img-left" width="435" height="240" alt="“崇尚劳动、热爱劳动、辛勤劳动、诚实劳动”，这16个字是对劳动精神的高度概括和生动诠释，为新时代坚持和弘扬劳动精神指明了方向，提供了遵循。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>“崇尚劳动、热爱劳动、辛勤劳动、诚实劳动”，这16个字是对劳动精神的高度概括和生动诠释，为新时代坚持和弘扬劳动精神指明了方向，提供了遵循。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">劳模精神</h3><a href="http://cpc.people.com.cn/n1/2021/0922/c64387-32232596.html" target="_blank"><img src="/NMediaFile/2021/0922/MAIN202109221009457749122042366.jpg" class="img-left" width="435" height="240" alt="广大劳动模范和先进工作者充分发挥示范带头作用，不断丰富劳模精神的时代内涵，激励广大劳动群众争做新时代的奋斗者，推动全社会形成尊重劳动、劳动光荣的良好风尚。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>广大劳动模范和先进工作者充分发挥示范带头作用，不断丰富劳模精神的时代内涵，激励广大劳动群众争做新时代的奋斗者，推动全社会形成尊重劳动、劳动光荣的良好风尚。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">载人航天精神</h3><a href="http://cpc.people.com.cn/n1/2021/0919/c64387-32231612.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101749208732811844290.jpg" class="img-left" width="435" height="240" alt="中国载人航天事业一次次在浩瀚太空刷新“中国高度”，同时也在中华民族的历史长河中培育铸就了“特别能吃苦、特别能战斗、特别能攻关、特别能奉献”的载人航天精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>中国载人航天事业一次次在浩瀚太空刷新“中国高度”，同时也在中华民族的历史长河中培育铸就了“特别能吃苦、特别能战斗、特别能攻关、特别能奉献”的载人航天精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">抗震救灾精神</h3><a href="http://cpc.people.com.cn/n1/2021/0913/c64387-32224838.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101744595095872300067.jpg" class="img-left" width="435" height="240" alt="在同特大地震灾害的艰苦搏斗中，我们的民族和人民展示出了十分崇高的精神。这就是万众一心、众志成城，不畏艰险、百折不挠，以人为本、尊重科学的伟大抗震救灾精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>在同特大地震灾害的艰苦搏斗中，我们的民族和人民展示出了十分崇高的精神。这就是万众一心、众志成城，不畏艰险、百折不挠，以人为本、尊重科学的伟大抗震救灾精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">抗击非典精神</h3><a href="http://cpc.people.com.cn/n1/2021/0909/c64387-32222002.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101734111869106367759.jpg" class="img-left" width="435" height="240" alt="面对突如其来的非典疫情，在党中央坚强领导下，全国人民以空前的团结和高昂的斗志，打响了一场防治疫病的人民战争，形成了抗击非典精神，取得了抗击非典阶段性重大胜利。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>面对突如其来的非典疫情，在党中央坚强领导下，全国人民以空前的团结和高昂的斗志，打响了一场防治疫病的人民战争，形成了抗击非典精神，取得了抗击非典阶段性重大胜利。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">抗洪精神</h3><a href="http://cpc.people.com.cn/n1/2021/0906/c64387-32218195.html" target="_blank"><img src="/NMediaFile/2021/0906/MAIN202109061308286656617712115.png" class="img-left" width="435" height="240" alt="广大干部群众和人民解放军、武警官兵坚决响应党和政府号召，发扬不怕累苦、不怕疲劳、不怕牺牲的精神斗志，坚守在防汛抗洪救灾第一线，涌现了许多先进典型和感人事迹，展现了中国人民众志成城、顽强拼搏、敢于胜利的英雄气概，书写了洪水无情人有情的人间大爱。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>广大干部群众和人民解放军、武警官兵坚决响应党和政府号召，发扬不怕累苦、不怕疲劳、不怕牺牲的精神斗志，坚守在防汛抗洪救灾第一线，涌现了许多先进典型和感人事迹，展现了中国人民众志成城、顽强拼搏、敢于胜利的英雄气概，书写了洪水无情人有情的人间大爱。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">女排精神</h3><a href="http://cpc.people.com.cn/n1/2021/0905/c64387-32217773.html" target="_blank"><img src="/NMediaFile/2021/1110/MAIN202111101729331968663451795.jpg" class="img-left" width="435" height="240" alt="女排精神代表着一个时代的精神，喊出了为中华崛起而拼搏的时代最强音。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>女排精神代表着一个时代的精神，喊出了为中华崛起而拼搏的时代最强音。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">特区精神</h3><a href="http://cpc.people.com.cn/n1/2021/0830/c64387-32211794.html" target="_blank"><img src="/NMediaFile/2021/0830/MAIN202108300916443996211042131.jpg" class="img-left" width="435" height="240" alt="40多年来，深圳、珠海、汕头、厦门、海南5个经济特区，像5颗闪亮的明珠镶嵌在祖国大地上。各经济特区解放思想、改革创新，勇担使命、砥砺奋进，孕育了“敢闯敢试、敢为人先、埋头苦干”的特区精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>40多年来，深圳、珠海、汕头、厦门、海南5个经济特区，像5颗闪亮的明珠镶嵌在祖国大地上。各经济特区解放思想、改革创新，勇担使命、砥砺奋进，孕育了“敢闯敢试、敢为人先、埋头苦干”的特区精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">两弹一星精神</h3><a href="http://cpc.people.com.cn/n1/2021/0828/c64387-32211052.html" target="_blank"><img src="/NMediaFile/2021/0830/MAIN202108300909396639797528185.jpeg" class="img-left" width="435" height="240" alt="在一穷二白的基础上起步，新中国仅用了10年左右的时间就创造了原子弹爆炸、导弹飞行和人造卫星上天的奇迹，取得了“两弹一星”事业的辉煌成就。与此同时，也孕育出了热爱祖国、无私奉献，自力更生、艰苦奋斗，大力协同、勇于登攀的“两弹一星”精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>在一穷二白的基础上起步，新中国仅用了10年左右的时间就创造了原子弹爆炸、导弹飞行和人造卫星上天的奇迹，取得了“两弹一星”事业的辉煌成就。与此同时，也孕育出了热爱祖国、无私奉献，自力更生、艰苦奋斗，大力协同、勇于登攀的“两弹一星”精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">大庆精神</h3><a href="http://theory.people.com.cn/n1/2021/0823/c40531-32203149.html" target="_blank"><img src="/NMediaFile/2021/0823/MAIN202108231048512000154064092.jpg" class="img-left" width="435" height="240" alt="60年来，几代大庆人艰苦创业、接力奋斗，在亘古荒原上建成我国最大的石油生产基地。大庆油田的卓越贡献已经镌刻在伟大祖国的历史丰碑上，大庆精神、铁人精神已经成为中华民族伟大精神的重要组成部分。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>60年来，几代大庆人艰苦创业、接力奋斗，在亘古荒原上建成我国最大的石油生产基地。大庆油田的卓越贡献已经镌刻在伟大祖国的历史丰碑上，大庆精神、铁人精神已经成为中华民族伟大精神的重要组成部分。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">焦裕禄精神</h3><a href="http://theory.people.com.cn/n1/2021/0820/c40531-32200915.html" target="_blank"><img src="/NMediaFile/2021/0820/MAIN202108201030167852203888197.jpg" class="img-left" width="435" height="240" alt="要特别学习弘扬焦裕禄同志“心中装着全体人民、唯独没有他自己”的公仆情怀，凡事探求就里、“吃别人嚼过的馍没味道”的求实作风，“敢教日月换新天”、“革命者要在困难面前逞英雄”的奋斗精神，艰苦朴素、廉洁奉公、“任何时候都不搞特殊化”的道德情操。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>要特别学习弘扬焦裕禄同志“心中装着全体人民、唯独没有他自己”的公仆情怀，凡事探求就里、“吃别人嚼过的馍没味道”的求实作风，“敢教日月换新天”、“革命者要在困难面前逞英雄”的奋斗精神，艰苦朴素、廉洁奉公、“任何时候都不搞特殊化”的道德情操。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">雷锋精神</h3><a href="http://cpc.people.com.cn/n1/2021/0816/c64387-32193834.html" target="_blank"><img src="/NMediaFile/2021/0816/MAIN202108161010356387183079126.jpg" class="img-left" width="435" height="240" alt="1963年3月，毛泽东同志亲笔题词，发出“向雷锋同志学习”的号召。50多年来，学雷锋活动蓬勃开展、长盛不衰，人民群众热情响应、广泛参与，雷锋精神的光芒愈加耀眼夺目，凝聚起推动民族奋进发展的磅礴力量。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>1963年3月，毛泽东同志亲笔题词，发出“向雷锋同志学习”的号召。50多年来，学雷锋活动蓬勃开展、长盛不衰，人民群众热情响应、广泛参与，雷锋精神的光芒愈加耀眼夺目，凝聚起推动民族奋进发展的磅礴力量。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">兵团精神</h3><a href="http://cpc.people.com.cn/n1/2021/0812/c64387-32190144.html" target="_blank"><img src="/NMediaFile/2021/0812/MAIN202108121043178295771961553.jpg" class="img-left" width="435" height="240" alt="2020年9月，习近平总书记在第三次中央新疆工作座谈会上强调：“要弘扬民族精神和时代精神，践行胡杨精神和兵团精神，激励各级干部在新时代扎根边疆、奉献边疆。”"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>2020年9月，习近平总书记在第三次中央新疆工作座谈会上强调：“要弘扬民族精神和时代精神，践行胡杨精神和兵团精神，激励各级干部在新时代扎根边疆、奉献边疆。”</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">抗美援朝精神</h3><a href="http://cpc.people.com.cn/n1/2021/0810/c64387-32187106.html" target="_blank"><img src="/NMediaFile/2021/0810/MAIN202108101117102121013541963.jpg" class="img-left" width="435" height="240" alt="在抗美援朝战争中，志愿军以“钢少气多”力克“钢多气少”，在极不对称、极为艰苦的条件下，打破了美军不可战胜的神话，创造了以弱胜强的典范，谱写了一曲曲英雄赞歌，锻造出伟大的抗美援朝精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>在抗美援朝战争中，志愿军以“钢少气多”力克“钢多气少”，在极不对称、极为艰苦的条件下，打破了美军不可战胜的神话，创造了以弱胜强的典范，谱写了一曲曲英雄赞歌，锻造出伟大的抗美援朝精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">伟大抗战精神</h3><a href="http://cpc.people.com.cn/n1/2021/0805/c64387-32182142.html" target="_blank"><img src="/NMediaFile/2021/0805/MAIN202108051043546881421712891.jpg" class="img-left" width="435" height="240" alt="中国人民在抗日战争的壮阔进程中孕育出伟大抗战精神，向世界展示了天下兴亡、匹夫有责的爱国情怀，视死如归、宁死不屈的民族气节，不畏强暴、血战到底的英雄气概，百折不挠、坚忍不拔的必胜信念。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>中国人民在抗日战争的壮阔进程中孕育出伟大抗战精神，向世界展示了天下兴亡、匹夫有责的爱国情怀，视死如归、宁死不屈的民族气节，不畏强暴、血战到底的英雄气概，百折不挠、坚忍不拔的必胜信念。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">延安精神</h3><a href="http://cpc.people.com.cn/n1/2021/0803/c64387-32179064.html" target="_blank"><img src="/NMediaFile/2021/0803/MAIN202108031325525809726080600.jpg" class="img-left" width="435" height="240" alt="1935年10月，中央红军经过二万五千里长征胜利抵达陕北，陕北自此成为中共中央的“落脚点”，也成为建立抗日民族统一战线、赢得抗日战争胜利、进而夺取人民解放战争胜利的“出发点”。十三载峥嵘岁月，孕育了永放光芒的延安精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>1935年10月，中央红军经过二万五千里长征胜利抵达陕北，陕北自此成为中共中央的“落脚点”，也成为建立抗日民族统一战线、赢得抗日战争胜利、进而夺取人民解放战争胜利的“出发点”。十三载峥嵘岁月，孕育了永放光芒的延安精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">长征精神</h3><a href="http://cpc.people.com.cn/n1/2021/0729/c64387-32173831.html" target="_blank"><img src="/NMediaFile/2021/0729/MAIN202107291445483732816693359.jpg" class="img-left" width="435" height="240" alt="伟大长征精神，作为中国共产党人红色基因和精神谱系的重要组成部分，已经深深融入中华民族的血脉和灵魂，成为社会主义核心价值观的丰富滋养，成为鼓舞和激励中国人民不断攻坚克难、从胜利走向胜利的强大精神动力。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>伟大长征精神，作为中国共产党人红色基因和精神谱系的重要组成部分，已经深深融入中华民族的血脉和灵魂，成为社会主义核心价值观的丰富滋养，成为鼓舞和激励中国人民不断攻坚克难、从胜利走向胜利的强大精神动力。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">苏区精神</h3><a href="http://cpc.people.com.cn/n1/2021/0726/c64387-32169200.html" target="_blank"><img src="/NMediaFile/2021/0729/MAIN202107291500316176679432513.jpg" class="img-left" width="435" height="240" alt="江西瑞金，叶坪革命旧址群，一座黛瓦灰墙的祠堂式建筑静静伫立。1931年11月，中华苏维埃第一次全国代表大会在这里召开，中华苏维埃共和国临时中央政府在这里成立。这是中国历史上第一个全国性的工农民主政权，它的成立谱写了中国共产党领导的革命根据地建设和红色政权建设的新篇章。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>江西瑞金，叶坪革命旧址群，一座黛瓦灰墙的祠堂式建筑静静伫立。1931年11月，中华苏维埃第一次全国代表大会在这里召开，中华苏维埃共和国临时中央政府在这里成立。这是中国历史上第一个全国性的工农民主政权，它的成立谱写了中国共产党领导的革命根据地建设和红色政权建设的新篇章。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">井冈山精神</h3><a href="http://cpc.people.com.cn/n1/2021/0722/c64387-32165741.html" target="_blank"><img src="/NMediaFile/2021/0722/MAIN202107221423384590325744870.jpg" class="img-left" width="435" height="240" alt="1927年10月，毛泽东同志率领秋收起义部队走上井冈山，开始工农武装割据斗争。在这里，中国共产党创建了第一个农村革命根据地，开辟了“农村包围城市、武装夺取政权”的中国革命道路，孕育了“坚定信念、艰苦奋斗，实事求是、敢闯新路，依靠群众、勇于胜利”的井冈山精神。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>1927年10月，毛泽东同志率领秋收起义部队走上井冈山，开始工农武装割据斗争。在这里，中国共产党创建了第一个农村革命根据地，开辟了“农村包围城市、武装夺取政权”的中国革命道路，孕育了“坚定信念、艰苦奋斗，实事求是、敢闯新路，依靠群众、勇于胜利”的井冈山精神。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->
<!-- 1个内容开始 start-->
          <div class="item-content">
            <!-- top开始 -->
            <div class="top"><h3 class="name-js" style="display: none;">伟大建党精神</h3><a href="http://cpc.people.com.cn/n1/2021/0719/c64093-32161465.html" target="_blank"><img src="/NMediaFile/2021/0719/MAIN202107191413200116239478665.jpg" class="img-left" width="435" height="240" alt="一百年前，中国共产党的先驱们创建了中国共产党，形成了坚持真理、坚守理想，践行初心、担当使命，不怕牺牲、英勇斗争，对党忠诚、不负人民的伟大建党精神，这是中国共产党的精神之源。"/></a><!-- 编辑填写的 显示在底部 -->
              <div class="desc">
               
                <div class="desc-tit">
                 
                  <div class="text">
                    <p>一百年前，中国共产党的先驱们创建了中国共产党，形成了坚持真理、坚守理想，践行初心、担当使命，不怕牺牲、英勇斗争，对党忠诚、不负人民的伟大建党精神，这是中国共产党的精神之源。</p>
                    
                  </div>
                </div>
                
              </div></div>
            <!-- top结束 -->
            <!-- desc-tit.html拷贝 过来 自动 显示在右侧-->
            <div class="right-desc-wrap">
              <h3></h3>
              <div class="text">
                <p>
                  
                </p>
                <div class="btn-wrap">
                  <a class="detail" href="http://people.cn">【详细】</a>
                </div>
              </div>
            </div>

          </div>
          <!-- 1个内容结束 end-->

      </div>
      <div class="links-wrap">
        <ul class="left-links"><li><a href='/n1/2021/0930/c64387-32242900.html' target="_blank">中国共产党人精神谱系第一批伟大精神正式发布</a></li>
<li><a href='/n1/2021/1208/c64387-32302134.html' target="_blank">弘扬探月精神 建设航天强国</a></li>
<li><a href='/n1/2021/1208/c64387-32302135.html' target="_blank">无悔青春 逐梦星河</a></li>
</ul>
        <ul class="left-links"><li><a href='/n1/2021/0930/c64387-32242900.html' target="_blank">中国共产党人精神谱系第一批伟大精神正式发布</a></li>
<li><a href='/n1/2021/1208/c64387-32302134.html' target="_blank">弘扬探月精神 建设航天强国</a></li>
<li><a href='/n1/2021/1208/c64387-32302135.html' target="_blank">无悔青春 逐梦星河</a></li>
</ul>
      </div>
    </div>
  </div>
</div>
<script>
- function () {
  // 生成导航
  var $allContents = $('.bk-zgjs .right-contents .item-content')
  var $allRightDesc = $('.bk-zgjs .right-desc-wrap')
  var navHTML = ''
  $('.bk-zgjs .right-contents .name-js').each(function () {
	navHTML += '<div class="swiper-slide"><div class="btn-js">$nav</div></div>'.replace('$nav', this.innerHTML)
  })
  $('.bk-zgjs .left-nav .swiper-wrapper').html(navHTML)
  $('.bk-zgjs .left-nav .swiper-slide').each(function (index) {
	$(this).attr('data-index', index)
  })
  $allContents.find('.desc-tit').each(function (index) {
	$allRightDesc.eq(index).html($(this).html())
  })
  var swiperJs = new Swiper('.swiper-container-js', {
	mode: 'vertical',
	slidesPerView: 6,
	autoplay: false, //可选选项，自动滑动
	loop: false, //可选选项，开启循
	onSlideChangeEnd: function (swiper) {
	  //console.log(swiper.activeIndex)
	  $allContents.eq(swiper.activeIndex).show().siblings().hide()
	}
  })
  setTimeout(function () {
	$('.bk-zgjs .left-nav .btn-js').click(function () {
	  var index = Number($(this).parent().attr('data-index'))
	  $allContents.eq(index).show().siblings().hide()
	  //swiperJs.activeIndex(index)
	})
  }, 1000);
  $('.bk-zgjs .arrowtop-js').click(function () {
	swiperJs.swipePrev();
  })
  $('.bk-zgjs .arrowbottom-js').click(function () {
	swiperJs.swipeNext();
  })
}()
</script>
<a id="ziliao" name="ziliao"></a>
<div class="bg01 clearfix" >
	<div class="w1200 tit2 clearfix"><img src="/img/MAIN/2021/11/121189/images/titn5.png" /></div>
	<div class="p6con clearfix">
		<div class="fl">
			<div class="pic3"><a href="http://cpc.people.com.cn/GB/64162/64168/index.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111061754016654730115659.jpg" width="427" height="61" alt="微信截图_20211106174940"/></a>
</div>
			<div class="pic3"><a href="http://dangjian.people.com.cn/GB/436844/index.html" target=_blank><img src="/NMediaFile/2021/1106/MAIN202111061753000202193469203.jpg" width="427" height="215" alt="微信截图_20211106175109"/></a>
</div>
			<ul class="list2"><li><a href="http://cpc.people.com.cn/n1/2017/1025/c414940-29608619.html" target="_blank">第十九届中央政治局会议</a> <a href="http://cpc.people.com.cn/n1/2017/1025/c414940-29608670.html" target="_blank">集体学习</a> <a href="http://cpc.people.com.cn/n1/2018/0103/c106101-29743350.html" target="_blank">第十九届中纪委全体会议</a> </li><li><a href="http://cpc.people.com.cn/19th/n1/2017/1025/c414305-29608266.html" target="_blank">十九届一中全会</a> <a href="http://cpc.people.com.cn/n1/2018/0119/c64094-29776109.html" target="_blank">二中全会</a> <a href="http://cpc.people.com.cn/n1/2018/0301/c64094-29840567.html" target="_blank">三中全会</a> <a href="http://cpc.people.com.cn/n1/2019/1031/c64094-31431615.html" target="_blank">四中全会</a> <a href="http://cpc.people.com.cn/n1/2020/1030/c64094-31911721.html" target="_blank">五中全会公报</a></li><li><a href="http://djsjk.people.cn/" target="_blank">党的建设数据库</a> <a href="http://dangshi.people.com.cn/GB/234123/index.html" target="_blank">党史资料库</a> <a href="http://dangjian.people.com.cn/GB/136058/427510/index.html" target="_blank">党务书库</a> <a href="http://dangjian.people.com.cn/n1/2021/0713/c117092-32156194.html" target="_blank">党徽党旗</a> <a href="http://dangjian.people.com.cn/GB/136058/426539/index.html" target="_blank">党员手册</a></li></ul>
		</div>
		<div class="fr">
			<h2>新时代 新经典</h2><p>    <a href="http://theory.people.com.cn/GB/68294/427900/index.html" target="_blank">学习习近平新时代中国特色社会主义思想重点数字图书专栏</a></p><h2>党校公开课</h2><p>    <a href="http://dangshi.people.com.cn/GB/437145/437552/index.html" target="_blank">民族复兴的呼唤与中国共产党的创立</a> <a href="http://dangshi.people.cn/GB/437145/437736/index.html" target="_blank">百年党史中的红色经典</a></p>
			<h4>学习文选<a class="more" href="http://theory.people.com.cn/GB/164319/index.html" target="_blank">更多+</a></h4>
          <div class="swiper7-outer">
            <div class="swiper-container swiper-container7">
              <div class="swiper-wrapper"><div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/0818/c40531-32197824.html" target="_blank"><img src="/NMediaFile/2021/1108/MAIN202111081728570831816244646.jpg" class="img-learn" width="102" height="148" alt="深入学习“七一”重要讲话精神&#13; 中国共产党团结带领中国人民又踏上了实现第二个百年奋斗目标新的赶考之路。点击下载PDF版"/></a><div class="desc7"><a href="http://theory.people.com.cn/n1/2021/0818/c40531-32197824.html" target="_blank"><h5>深入学习“七一”重要讲话精神</h5>
 <p>中国共产党团结带领中国人民又踏上了实现第二个百年奋斗目标新的赶考之路。</p><p style="padding-top: 20px;"><a href="http://download.people.com.cn/dangwang/one16292548781.pdf" download="" target="_blank" style="color: #b32e23;" >点击下载PDF版</a></p></a></div></div>
<div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/0918/c40531-32231201.html" target="_blank"><img src="/NMediaFile/2021/1108/MAIN202111081731358321014643560.jpg" class="img-learn" width="102" height="148" alt="在高质量发展中促进共同富裕&#13; 实现共同富裕既是中国共产党的初心与使命，也是中国社会主义现代化建设的本质要求。点击下载PDF版&#13;"/></a><div class="desc7"><a href="http://theory.people.com.cn/n1/2021/0918/c40531-32231201.html" target="_blank"><h5>在高质量发展中促进共同富裕</h5>
 <p>实现共同富裕既是中国共产党的初心与使命，也是中国社会主义现代化建设的本质要求。</p><p style="padding-top: 20px;"><a href="http://download.people.com.cn/dangwang/one16317570101.pdf" download="" target="_blank" style="color: #b32e23;" >点击下载PDF版</a></p>
</a></div></div>
<div class="swiper-slide"><a href="http://theory.people.com.cn/n1/2021/1019/c40531-32257956.html" target="_blank"><img src="/NMediaFile/2021/1108/MAIN202111081730266512048686197.jpg" class="img-learn" width="102" height="148" alt="深入实施新时代人才强国战略&#13; 我们党始终重视培养人才、团结人才、引领人才、成就人才，团结和支持各方面人才建功立业。点击下载PDF版"/></a><div class="desc7"><a href="http://theory.people.com.cn/n1/2021/1019/c40531-32257956.html" target="_blank"><h5>深入实施新时代人才强国战略</h5>
 <p>我们党始终重视培养人才、团结人才、引领人才、成就人才，团结和支持各方面人才建功立业。</p><p style="padding-top: 20px;"><a href="http://download.people.com.cn/dangwang/one16340950531.pdf" download="" target="_blank" style="color: #b32e23;" >点击下载PDF版</a></p></a></div></div>
</div>
            </div>
            <img src="/img/MAIN/2020/12/120674/images/arrow-left10.png" alt="" class="arrow-left7">
            <img src="/img/MAIN/2020/12/120674/images/arrow-right10.png" alt="" class="arrow-right7">
          </div>
		</div>
	</div>
</div>
<div id="copyright" class="copyright clearfix">人 民 网 版 权 所 有 ，未 经 书 面 授 权 禁 止 使 用<br />
Copyright &copy; 1997-2021 by www.people.com.cn. all rights reserved</div> 
</div>
<style type="text/css">
.topb{position:fixed;bottom:80px; right:20px;font-size:18px;font-family:"Microsoft YaHei";background:url(http://www.people.com.cn/img/2020peopleindex/img/topb.png) no-repeat top center;width:130px;height:50px;line-height:50px;padding-left:40px;cursor:pointer; display:none;z-index:111}
.topb:hover{color:#fff;background:url(http://www.people.com.cn/img/2020peopleindex/img/topba.png) no-repeat top center;}
</style>
<div class="topb">返回顶部</div>
<script type="text/javascript">
$(document).ready(function() {
	$(document).scroll(function(){
		var bkTop=$(this).scrollTop();
		if(bkTop > 200){
			$(".topb").show()
		}
		else{
			$(".topb").hide()	
		}			
	})	
	$(".topb").click(function(){
        $('html , body').animate({scrollTop: 0},500);
    });	
});
</script>
<script src="/img/MAIN/2021/11/121189/mainh.js" type="text/javascript" charset="utf-8"></script>

<script src="http://www.people.com.cn/img/2016wb/jweixin-1.0.0.js" type="text/javascript"></script><script type="text/javascript">      
	var wxData = {
		"imgUrl": "http://www.people.com.cn/img/2016wb/images/logo_share.jpg",
		"link": window.location.href.split('?')[0],
		"desc": "聚焦十九届六中全会",
		"title": "聚焦十九届六中全会"
	};
</script><script src="http://www.people.com.cn/img/2016wb//WeiXinDatatit2020.js" type="text/javascript"></script>
<script src="http://tools.people.com.cn/css/2010tianrun/webdig_test.js" language="javascript" type="text/javascript" async></script>
</body>
</html>
