<div class="book with-summary">

<div class="head">

<div class="head_box">

# [](javascript:; "_('微信公众平台 小程序')")

<div class="header_ctrls">

*   [介绍](https://mp.weixin.qq.com/debug/wxadoc/introduction/index.html?t=2017616)
*   [设计](https://mp.weixin.qq.com/debug/wxadoc/design/index.html?t=2017616)
*   [开发](https://mp.weixin.qq.com/debug/wxadoc/dev/index.html?t=2017616)
*   [运营](https://mp.weixin.qq.com/debug/wxadoc/product/index.html?t=2017616)
*   [数据](https://mp.weixin.qq.com/debug/wxadoc/analysis/index.html?t=2017616)

</div>

</div>

</div>

<div class="sub_nav_box">

<div class="sub_nav_inner">

<div class="book-summary-opr" id="js-book-summary-opr"><a class="book-summary-btn"></a></div>

<div class="top_sub_nav">

<div class="top_title_wap"><span class="icon_title icon_dev"></span>

微信小程序开发文档

</div>

*   [简易教程](../)
*   [框架](MINA.html)
*   [组件](../component/)
*   [API](../api/)
*   [工具](../devtools/devtools.html)
*   [Q&A](../qa.html)

</div>

<div id="book-search-input" role="search">

<form><label for="search-input" class="search-icon" id="js-search-icon"></label><input type="text" id="search-input" name="search-input" placeholder="搜索"> </form>

</div>

</div>

</div>

<div class="book-summary">

<div class="book-summary-home" id="js-summary-home"><a><span class="icon_home_s icon_dev"></span><span class="s_title_2">开发文档首页</span></a></div>

<nav role="navigation">

*   [目录结构](structure.html)
*   [配置](config.html)
*   [逻辑层](app-service/)
    *   [注册程序](app-service/app.html)
    *   [场景值](app-service/scene.html)
    *   [注册页面](app-service/page.html)
    *   [路由](app-service/route.html)
    *   [模块化](app-service/module.html)
    *   [API](app-service/api.html)
*   [视图层](view/)
    *   [WXML](view/wxml/)
        *   [数据绑定](view/wxml/data.html)
        *   [列表渲染](view/wxml/list.html)
        *   [条件渲染](view/wxml/conditional.html)
        *   [模板](view/wxml/template.html)
        *   [事件](view/wxml/event.html)
        *   [引用](view/wxml/import.html)
    *   [WXSS](view/wxss.html)
    *   [组件](view/component.html)
*   [基础库](client-lib.html)
*   [兼容](compatibility.html)
*   [性能](performance.html)

</nav>

</div>

<div class="book-body">

<div class="body-inner">

<div class="page-wrapper" tabindex="-1" role="main">

<div class="page-inner">

<div id="book-search-results">

<div class="search-noresults">

<section class="normal markdown-section">

# 文件结构

小程序包含一个描述整体程序的 app 和多个描述各自页面的 page。

一个小程序主体部分由三个文件组成，必须放在项目的根目录，如下：

<table>

<thead>

<tr>

<th>文件</th>

<th>必填</th>

<th>作用</th>

</tr>

</thead>

<tbody>

<tr>

<td>[app.js](app-service/app.html)</td>

<td>是</td>

<td>小程序逻辑</td>

</tr>

<tr>

<td>[app.json](config.html)</td>

<td>是</td>

<td>小程序公共设置</td>

</tr>

<tr>

<td>[app.wxss](view/wxss.html)</td>

<td>否</td>

<td>小程序公共样式表</td>

</tr>

</tbody>

</table>

一个小程序页面由四个文件组成，分别是：

<table>

<thead>

<tr>

<th>文件类型</th>

<th>必填</th>

<th>作用</th>

</tr>

</thead>

<tbody>

<tr>

<td>[js](app-service/page.html)</td>

<td>是</td>

<td>页面逻辑</td>

</tr>

<tr>

<td>[wxml](view/wxml/)</td>

<td>是</td>

<td>页面结构</td>

</tr>

<tr>

<td>[wxss](view/wxss.html)</td>

<td>否</td>

<td>页面样式表</td>

</tr>

<tr>

<td>[json](config.html#pagejson)</td>

<td>否</td>

<td>页面配置</td>

</tr>

</tbody>

</table>

**注意：为了方便开发者减少配置项，我们规定描述页面的这四个文件必须具有相同的路径与文件名。**

</section>

</div>

<div class="search-results">

<div class="has-results">

# <span class="search-results-count"></span>个结果 "<span class="search-query"></span>"

</div>

<div class="no-results">

# 没有找到相关内容 "<span class="search-query"></span>"

</div>

</div>

</div>

</div>

</div>

<div class="foot" id="footer">

*   [关于腾讯](http://www.tencent.com/zh-cn/index.shtml)
*   [文档中心](https://mp.weixin.qq.com/debug/wxadoc/introduction/index.html?t=1484641676&t=2017616)
*   [辟谣中心](https://mp.weixin.qq.com/cgi-bin/opshowpage?action=dispelinfo&lang=zh_CN&begin=1&count=9)
*   [客服中心](http://kf.qq.com/faq/120911VrYVrA1509086vyumm.html)
*   [联系邮箱](mailto:weixinmp@qq.com)
*   Copyright © 2012-<span id="s_copyright_year"></span> Tencent. All Rights Reserved.

</div>

</div>

[](MINA.html)[](config.html)</div>

</div>