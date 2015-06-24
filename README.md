# 12119247 王庭諭

###1.	navbar的按鈕分別有三個設定
‵`<ul class=’nav nav-tabs’>….</ul>‵`
‵`<ul class=’nav nav-pills’>….</ul>‵`
``<ul class=’nav nav-navbar-nav navbar-right’>….</ul>``
###2.更換導覽列顏色 分別有兩個設定
設定於 ``<div class=’container navbar navbar-default’>`` 白色底黑字
設定於 ``<div class=’container navbar navbar-inverse’>`` 黑色底白字
###3.	設定導覽列會不會跟著畫面跑的時候
- 在``<div class=’navbar navbar-default navbar-static-top’>….</div>``
將navbar-static-top的部分設定為如此時會跟著畫面跑
若將上述部分更改為navbar-fixed-top時則不會跟著畫面捲動
###4.	當畫面須由手機等裝置開啟時(Extra Small) 須由java設定
###5.	若要收起導覽列的內容 須設定navbar屬性設定 (在navbar後面加上.collapse)
###6.	設定縮小畫面時的導覽列為一按鈕時需設定
``<button type=’button’ class=’navbar-toggle’>``
 ``<span class=’sr-only’>Toggle navigation</span>``
`` <span class=’icon-bar’></span>``
 ``<span class=’icon-bar’></span>``
``</button>``
###7.	如需設定導覽列的下放按鈕
我們需先設定一個連結 也就是
``<a href=’#’>@@@@ <span class=’caret’></span></a>``
###8.	如需設定導覽列下放按鈕之內容
我們需在上述條件設定下繼續設定按鈕
``<a href=’#’>@@@@ <span class=’caret’></span></a>``
``<ul>``
 ``<li><a href=’story.html>Our Story</a></li>``
 ``<li><a href=’contact.html>Contact Us</a></li>``
 ``<li><a href=’/blog>Blog</a></li>``
 ``<li><a href=’臉書連結>facebook</a></li>``
 ``<li><a href=’推特連結>twitter</a></li>``
``</ul> ``
