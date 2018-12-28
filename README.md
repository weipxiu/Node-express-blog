# 唯品秀博客 - Wordpress主题

# https://www.weipxiu.com

> 一款基于jquery2.1.4开发的wordpress主题2.0版

> 主题介绍：https://www.weipxiu.com/?cat=10

## 使用方式

``` bash
# 步骤

1、本项目采用gulp自动化构建，可通过git克隆到本地，然后运行npm install安装依赖，接着运行gulp即可压缩打包整个项目，如不需要
   打包压缩代码等一系列工具功能可直接下载即可，然后找到项目文件的src目录，里面即是项目主题源码

2、将主题文件放在：/htdocs/wp-content/themes/目录下

3、在wordpress后台安装WP-PageNavi插件

4、删除首页index.php中的邮箱订阅php代码(需要借助插件配置才可以使用的，当然，你也可以折腾，插件名称：WordPress Mailer)

5、全局替换所有链接为https://www.weipxiu.com地址，设置为自己的域名地址

6、如果你的网站设置了https头，那么你应该将主题文件php模板页所有链接http改为https，否则可能报错找不到文件

7、在wordpress后台新建分类目录，新建后将鼠标放在分类名称上，在浏览器左下角出现链接，其中有个id=xx，
将这个id对应的值设置替换给主题文件里的category-x的x，重新上传修改过名字的文件，如有其它问题，欢迎打扰

8、文字枯燥还是不知道说的啥意思？亲自录制的教程视频：链接：https://pan.baidu.com/s/19wibJjeagvLRFOuUV2GvEQ 密码：6u6c

9、如果喜欢，请多多打赏。

```
<img src="https://raw.githubusercontent.com/weipxiu/weipxiu/master/src/images/zhiwei.png">

## 备注说明

> 1、wordpress主题制作有特别要求，例如主题根目录必须存在header.php、index.php、footer.php、style.css，否则是不认，无法加载的。因此不用觉得某些文件摆放不合理，存在必定有意义

> 2、为了更佳浏览效果，该主题对IE10及其以下浏览器作了屏蔽跳转

> 3、基于css文件作了根据终端分割，所以你会看到主题根目录下有三个css文件，有利有弊，不做过多评论

> 4、源码开放供大家使用并修改，但在使用过程中底部请保留"唯品秀"版权说明，
  即：在footer.php源码中请不要去掉：<p>本站主题由<a href="https://www.weipxiu.com/" class="highlight">WEIPXIU.COM</a>免费提供</p>

## 项目文件说明
``` bash
│  category-1.php    //穿梭机
│  category-10.php   //关于博客
│  category-8.php    //碎言碎语
│  category.php   //通用列表模板
│  comments.php   //评论模块
│  favicon.ico  //网页浏览器标签icon
│  footer.php  //底部
│  functions.php   //主题核心函数
│  header.php  //头部
│  index.html  //测试页面
│  index.php   //首页
│  page.php    //注册
│  reminder.php   //低版本浏览器重定向
│  screenshot.png //wordpress主题展示图片
│  search.php  //搜索模板
│  sidebar.php    //右侧栏目
│  single.php  //文章详情
│  style.css   //PC端样式
│  thanks.php  //特别鸣谢
│  theme-options.php  //主题设置
│  
├─css
│      PingFangSC-Regular.woff   //一些字体文件
│      sf-pro-display_medium.woff2
│      sf-pro-display_regular.woff2
│      sf-pro-display_semibold.woff2
│      sf-pro-text_bold.woff2
│      sf-pro-text_regular.woff2
│      sf-pro-text_semibold.woff2
│      style-ios.css    //针对手机端样式
│      style-ipd.css    //针对ipd平板样式
│      swiper.min.css   //移动端轮播swiper样式
│      video-js.css 
│      
├─font-awesome-4.7.0    //国外比较有名的icon图标库
│          
├─images    //图片资源
│      
├─js
│  │  ajax_wordpress.js    //用于分页ajaxs刷新
│  │  canvas-nest.min.js 
│  │  date.js  //时光机数据
│  │  hovertreewelcome.js
│  │  index.js    //整个网站的js全局
│  │  javascript.js  //只针对首页的js文件
│  │  jquery-2.1.4.min.js
│  │  main.js
│  │  rem.js
│  │  swiper.min.js  //移动端的swiper轮播插件
│  │  xfg_banner.js
│  │  zui.min.js
│  │  
│  ├─video.js 
│  │      video.min.js
│  │      videojs-ie8.min.js
│  │      zh-CN.js
│  │      zh-CN.json
│  │      
│  └─xfg_banner   //PC端首页banner
│          banner-effect.js
│          banner.js
│          effect.js
│          jquery.min.js
│          utils.js
│          
└─music  /导航音频文件
 ```       
<!-- <h2>使用当前主题网站</h2>

>不完全统计

> 爱前端  https//www.huanggr.cn/
> 博学老头  https://www.boxuelaotou.com/ -->


