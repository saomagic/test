<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
<title><data:blog.pageTitle/></title>
<b:include data='blog' name='all-head-content'/>
<link href='http://fonts.googleapis.com/css?family=Lato:400,700,400italic|Yanone+Kaffeesatz' rel='stylesheet' type='text/css'/>
<script src='http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js' type='text/javascript'/>
<b:skin><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name:        Pinfinity       
Author :     http://www.soratemplates.com
Designer:    http://www.cssigniter.com
Date:        August 2012
License:  This free Blogger template is licensed under the Creative Commons Attribution 3.0 License, which permits both personal and commercial use. However, to satisfy the 'attribution' clause of the license, you are required to keep the footer links intact which provides due credit to its authors. For more specific details about the license, you may visit the URL below:
http://creativecommons.org/licenses/by/3.0
----------------------------------------------- */
body#layout .header-wgt,body#layout nav,#sidebar,#navbar,.date-header,#credit,.feed-links,.post-location,.post-share-buttons,.post-icons{display: none !important;}
body,h1,h2,h3,h4,h5,ul,li,a,p,span,img,dd{margin:0;padding:0;list-style:none;text-decoration:none;border:none;outline:none}
body#layout #Header .widget{float:none}

body {
    background: #F6F6F3;
    color: #737373;
    font: 13px/1.2 Lato,"Helvetica Neue",Helvetica,Arial,sans-serif;
    height: 100%;
    text-rendering: optimizelegibility;
}

a {color: #5f91ab;}
a:focus,a:active,a:hover {color: #81b1ca;}
h1, h2, h3, h4, h5{color: #5F91AB;font-weight: normal;font-family: 'Yanone Kaffeesatz','Helvetica Neue',Helvetica,Arial,sans-serif;}

#Header {
    border-top: 7px solid #C4D9E4;
    background: #FAFAFA;
    text-shadow: 1px 1px 0 #FFFFFF;
}
#Header1{margin:0 !important}
#site-head {
  padding: 20px 0 0 0;
  border-bottom: 1px solid #dddddd;
  border-top: 1px solid #FFFFFF;
}

.group:after {
  content:" ";
  display:block;
  height:0;
  clear:both;
  visibility:hidden;
}

.wrap { margin: 0 auto; max-width: 1635px; padding: 0 10px; }
.header-wgt {float: right;margin-bottom:20px}
#Header .widget {float: left;margin-top: 8px;margin-bottom: 0;}
#Header .widget_ci_social_widget {margin-right: 40px;}
a.icn{width:24px;height:24px;background-image:url(https://lh4.googleusercontent.com/-PByEm-8Odys/UDMDIZ5X9sI/AAAAAAAADRg/iognh91MurI/s500/social-icons.png);background-repeat:no-repeat;float:left;margin-right:5px;text-indent:-999em;cursor:pointer;-webkit-transition:all 0s linear 0s;-moz-transition:all 0s linear 0s;-o-transition:all 0s linear 0s;transition:all 0s linear 0s}
.icn:focus,.icn:active{outline:none}
.icn.twitter{background-position:-31px -1px}
.icn.twitter:hover{background-position:-31px -31px}
.icn.facebook{background-position:0 -1px}
.icn.facebook:hover{background-position:0 -31px}
.icn.youtube{background-position:-218px -1px}
.icn.youtube:hover{background-position:-218px -31px}
.icn.pinterest{background-position:-313px -1px}
.icn.pinterest:hover{background-position:-313px -31px}

.fLabel { top: 15px !important; left: 9px !important;line-height: 0 !important;}
.searchform .fLabel {left: 12px !important;}
.searchform {
  position: relative;
  line-height: 0;
  padding: 0;
  margin: 0;
  box-sizing: content-box;
  height: 0;
  margin-top: -3px;
}

.searchform div {
  line-height: 0;
  margin: 0;
  padding: 0;
  display: inline;
}

.searchform .s {
  margin: 0;
  float: left;
  font: inherit;
  font-size: 12px;
  border: 1px solid #f0f0f0;
  border-top: 1px solid #dcdcdc;
  border-left: 1px solid #dcdcdc;
  border-right: none;
  padding: 7px 10px 8px;
  /*box-shadow: 0 1px #FFFFFF, 0 1px rgba(34, 25, 25, 0.05) inset*/
  line-height: 1;
  width: 200px;
  display: block;
  -moz-transition: all 0.2s linear;
  -webkit-transition: all 0.2s linear;
  -o-transition: all 0.2s linear;
  transition: all 0.2s linear;
  background: none repeat scroll 0 0 #F8F8F8;
  color: #737373;
}

.searchform .s:focus {
  -moz-box-shadow: 1px 1px 3px 0 rgba(0, 0, 0, 0.12) inset;
  -webkit-box-shadow: 1px 1px 3px 0 rgba(0, 0, 0, 0.12) inset;
  -o-box-shadow: 1px 1px 3px 0 rgba(0, 0, 0, 0.12) inset;
  box-shadow: 1px 1px 3px 0 rgba(0, 0, 0, 0.12) inset;
}

.searchform .searchsubmit {
  float: left;
  display: block;
  top: 0;
  right: 0;
  cursor: pointer;
  border-radius: 0;
  border: 1px solid #dcdcdc;
  border-top: 1px solid #dcdcdc;
  border-left: 1px solid #dcdcdc;
  padding: 8px 8px 6px;
  background-color: #f3f3f3;
  background-image: linear-gradient(bottom, rgb(237,237,237) 0%, rgb(250,250,250) 100%);
  background-image: -o-linear-gradient(bottom, rgb(237,237,237) 0%, rgb(250,250,250) 100%);
  background-image: -moz-linear-gradient(bottom, rgb(237,237,237) 0%, rgb(250,250,250) 100%);
  background-image: -webkit-linear-gradient(bottom, rgb(237,237,237) 0%, rgb(250,250,250) 100%);
  background-image: -ms-linear-gradient(bottom, rgb(237,237,237) 0%, rgb(250,250,250) 100%);
  background-image: -webkit-gradient(
    linear,
    left bottom,
    left top,
    color-stop(0, rgb(237,237,237)),
    color-stop(1, rgb(250,250,250))
  );
  line-height: 0;
  box-sizing: content-box;
  -moz-box-shadow: inset 1px 1px 0 0 #FFFFFF;
  -webkit-box-shadow: inset 1px 1px 0 0 #FFFFFF;
  -o-box-shadow: inset 1px 1px 0 0 #FFFFFF;
  box-shadow: inset 1px 1px 0 0 #FFFFFF;
  -moz-transition: 0s all 0s linear;
  -webkit-transition: 0s all 0s linear;
  -o-transition: 0s all 0s linear;
  transition: 0s all 0s linear;
}

.searchform .searchsubmit img {line-height: 1;}

.searchform .searchsubmit:active {
  -moz-box-shadow: 1px 1px 3px 0 rgba(0, 0, 0, 0.12) inset;
  -webkit-box-shadow: 1px 1px 3px 0 rgba(0, 0, 0, 0.12) inset;
  -o-box-shadow: 1px 1px 3px 0 rgba(0, 0, 0, 0.12) inset;
  box-shadow: 1px 1px 3px 0 rgba(0, 0, 0, 0.12) inset;
}

#header{float:left;}
#header-inner{margin-top:-10px}
#header,#header a {text-shadow: 1px 1px 0 #FFFFFF;color: #5F91AB }
#header h1 {font-size:32px}
#header img {max-height:48px;padding-top:10px}

nav {padding: 12px 0 0;border-top: 1px solid #FFFFFF;border-bottom: 1px solid #dddddd;}
#navigation {text-align: center;list-style: none;margin: 0;padding: 0;}
#navigation a {
  color: #676767;
  font-weight: bold;
  font-size: 1.076923076923077em;
  display: block;
  text-align: left;
}

#navigation > li {display: inline-block;margin-right: 20px;position: relative;}
#navigation > li a {padding-bottom: 14px;}
#navigation > li a:hover, #navigation .current-menu-item > a, #navigation .current_page_item > a,#navigation li.sfHover > a {color: #000;}

#navigation > li > ul {
  position: absolute;
  z-index: 1500;
  left: -14px;
  display: block;
  margin: 0;
  padding: 0;
  list-style: none;
  background: #FAFAFA;
  -webkit-border-radius: 0 0 3px 3px;
  -moz-border-radius: 0 0 3px 3px;
  -o-border-radius: 0 0 3px 3px;
  border-radius: 0 0 3px 3px;
  -moz-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.2);
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.2);
  -o-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.2);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.2);
  top: -999em;
}

#navigation > li > ul li {display: block;}

#navigation > li > ul li a {
  white-space: nowrap;
  font-weight: bold;
  padding: 10px 40px 10px 15px;
  font-size: 13px;
}

#navigation > li:hover > ul {top: auto;}

nav select {display: none;}

#navigation ul ul {
  list-style: none;
  margin: 0;
  padding: 0;
  background: #fff;
  text-align: left;
  border-top: 1px solid #f3f3f3;
  border-bottom: 1px solid #f3f3f3;
}

#navigation ul ul li a {font-size: 0.9em;}
#navigation > li > ul {border-top: 4px solid #C4D9E4;}
#navigation > li > ul li a:hover {background: #e8eef1;}
#page {min-height: 100%;position: relative;}
#main {padding: 40px 0 80px;}
.wrap {margin: 0 auto;max-width: 1635px;padding: 0 10px;}
#entry-list {margin-left: -16px;}
#box-container{max-width: 670px;margin:0 auto}

.isotope,.isotope .isotope-item {
  -webkit-transition-duration: 0.8s;
  -moz-transition-duration: 0.8s;
  -ms-transition-duration: 0.8s;
  -o-transition-duration: 0.8s;
  transition-duration: 0.8s;
}

.isotope {
  -webkit-transition-property: height, width;
  -moz-transition-property: height, width;
  -ms-transition-property: height, width;
  -o-transition-property: height, width;
  transition-property: height, width;
}

.isotope .isotope-item {
  -webkit-transition-property: -webkit-transform, opacity;
  -moz-transition-property:    -moz-transform, opacity;
  -ms-transition-property:     -ms-transform, opacity;
  -o-transition-property:         top, left, opacity;
  transition-property:         transform, opacity;
}

.isotope.no-transition,
.isotope.no-transition .isotope-item,
.isotope .isotope-item.no-transition {
  -webkit-transition-duration: 0s;
  -moz-transition-duration: 0s;
  -ms-transition-duration: 0s;
  -o-transition-duration: 0s;
  transition-duration: 0s;
}

.box {
  background: #fff;
  -moz-border-radius: 4px;
  -webkit-border-radius: 4px;
  -o-border-radius: 4px;
  border-radius: 4px;
  -moz-box-shadow: 0 1px 1px rgba(0,0,0,0.31);
  -webkit-box-shadow: 0 1px 1px rgba(0,0,0,0.31);
  -o-box-shadow: 0 1px 1px rgba(0,0,0,0.31);
  box-shadow: 0 1px 1px rgba(0,0,0,0.31);
}

.box .entry-content-cnt { border-bottom: 1px solid #E6E6E6; padding: 8px; }
.box .entry-desc {
  padding: 8px 12px 10px;
  background: #f7f7f7;
  border-top: 1px solid #fff;
  -moz-border-radius: 0 0 4px 4px;
  -webkit-border-radius: 0 0 4px 4px;
  -o-border-radius: 0 0 4px 4px;
  border-radius: 0 0 4px 4px;
}

.entry h3 { font-size: 1.53846em;margin-bottom: 12px;}
.entry-intro {padding: 4% 3% 3.2%;position: relative;}
.entry-intro h1 {
    font-size: 2.38462em;
    line-height: 0.9;
    margin-bottom: 5px;
    max-width: 88%;
}
.post-body{line-height: 1.5;}
.post-body img { max-width:600px; }
.thumb{
  display:block;
  width:244px;
  height:auto;
  -moz-transition: all 0.2s linear;
  -webkit-transition: all 0.2s linear;
  -o-transition: all 0.2s linear;
  -ms-transition: all 0.2s linear;
  transition: all 0.2s linear;
}

.thumb:hover {opacity: 0.6;}
blockquote:before,blockquote:after {content:""; border-left: 3px solid #C4D9E4;color: #9A9A9A;font-size: 1.24em;line-height: 1.4;margin-bottom: 1em;padding-left: 4%;}

.comments-no {
    background: url(https://lh6.googleusercontent.com/-dK2CacKrHUY/UDMDJVdJ5JI/AAAAAAAADRs/PSQ7X9mPIMk/s326/sprites.png) no-repeat scroll 0 2px transparent;
    color: #A3A3A3;
    font-size: 12px;
    padding-left: 16px;
    float: left;
}
.entry-permalink {
    background: url(https://lh6.googleusercontent.com/-dK2CacKrHUY/UDMDJVdJ5JI/AAAAAAAADRs/PSQ7X9mPIMk/s326/sprites.png) no-repeat scroll 0 -49px transparent;
    cursor: pointer;
    float: right;
    height: 16px;
    text-indent: -999em;
    width: 16px;
}
.fb-home {
    float: left;
    height: 20px;
    max-width: 79px;
    margin: -2px 0 0 10px;
}

#comments{overflow:hidden}
#comments h4{display:inline;padding:10px;line-height:40px}
#comments h4,.comments .comment-header,.comments .comment-thread.inline-thread .comment{position:relative}
#comments h4,.comments .continue a{background:#5F91AB}
#comments h4,.comments .user a,.comments .continue a{font-size:16px}
#comments h4,.comments .continue a{font-weight:normal;color:#fff}
#comments h4:after{content:"";position:absolute;bottom:-10px;left:10px;border-top:10px solid #5F91AB;border-right:20px solid transparent;width:0;height:0;line-height:0}
#comments .avatar-image-container img{border:0}
.comment-thread{color:#111}
.comment-thread a{color:#777}
.comment-thread ol{margin:0 0 20px}
.comment-thread .comment-content a,.comments .user a,.comments .comment-thread.inline-thread .user a{color:#5F91AB}
.comments .avatar-image-container,.comments .avatar-image-container img{width:48px;max-width:48px;height:48px;max-height:48px}
.comments .comment-block,.comments .comments-content .comment-replies,.comments .comment-replybox-single{margin-left:60px}
.comments .comment-block,.comments .comment-thread.inline-thread .comment{border:1px solid #ddd;background:#f9f9f9;padding:10px}
.comments .comments-content .comment{margin:15px 0 0;padding:0;width:100%;line-height:1em}
.comments .comments-content .icon.blog-author{position:absolute;top:-12px;right:-12px;margin:0;background-image: url(https://lh3.googleusercontent.com/-7T8uy_ugxpQ/UDL3A59N8dI/AAAAAAAADRI/7Fsigu8Suyo/s36/author.png);width:36px;height:36px}
.comments .comments-content .inline-thread{padding:0 0 0 20px}
.comments .comments-content .comment-replies{margin-top:0}
.comments .comment-content{padding:5px 0;line-height:1.4em}
.comments .comment-thread.inline-thread{border-left:1px solid #ddd;background:transparent}
.comments .comment-thread.inline-thread .comment{width:auto}
.comments .comment-thread.inline-thread .comment:after{content:"";position:absolute;top:10px;left:-20px;border-top:1px solid #ddd;width:10px;height:0px}
.comments .comment-thread.inline-thread .comment .comment-block{border:0;background:transparent;padding:0}
.comments .comment-thread.inline-thread .comment-block{margin-left:48px}
.comments .comment-thread.inline-thread .user a{font-size:13px}
.comments .comment-thread.inline-thread .avatar-image-container,.comments .comment-thread.inline-thread .avatar-image-container img{width:36px;max-width:36px;height:36px;max-height:36px}
.comments .continue{border-top:0;width:100%}
.comments .continue a{padding:10px 0;text-align:center}
.comment .continue{display:none}
#comment-editor{width:103%!important}
.comment-form{width:100%;max-width:100%}

#footer {
  background: #fafafa;
  text-shadow: 1px 1px 0 #fff;
  font-size: 12px;
  text-align: center;
  border-top: 1px solid #dddddd;
  position: absolute;
  height: 50px;
  bottom: 0;
  width: 100%;
  border-bottom: 7px solid #C4D9E4;
}

#footer .wrap {padding: 20px 0;}
#footer a {text-shadow: 1px 1px 0 #FFFFFF;}

#blog-pager-newer-link {float: left;}
#blog-pager-older-link {float: right;}
#blog-pager { margin:0; padding:10px 0; text-align: center; clear:both; }
#PopularPosts1 img {float:left;margin:5px 10px 0 5px;padding:0}
#PopularPosts1 dd {margin:5px 0 10px}
.status-msg-body {position:relative !important}
.CSS_LIGHTBOX { z-index: 9999 !important; }
]]></b:skin>
<style tyle='text/css'>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
.box {
  float: left;
  width: 260px;
  margin-left: 15px;
  margin-bottom: 15px;
}
#box-container {max-width: 100%;}
<b:else/>
.post-body{border-bottom: 1px solid #E6E6E6;padding: 0 3% 3%;}
</b:if>
</style>
<script type='text/javascript'>//<![CDATA[
eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('f g(a){h p=i.j(a),7="",4=p.k("4");l(4.m>=1)7=\'<4 2="n" 8="\'+4[0].8+\'" />\';p.o=\'<3 2="6-q-r"><a 5="\'+y+\'">\'+7+"</a></3>"+\'<3 2="6-s"><9><a 5="\'+y+\'">\'+x+\'</a></9><3 2="6-u v"><a 2="w-b" 5="\'+t+\'">\'+z+\'</a><c 2="A-B" C="D" E="0" F="b" 8="G://H.I.J/K/d.L?5=\'+y+\'&M=e&N=O&P=e&Q=R&S=d&T=U"></c><a V="\'+x+\'" 2="6-W" 5="\'+y+\'"></a><3 2="X"></3></3></3>\'};',60,60,'||class|div|img|href|entry|imgtag|src|h3||no|iframe|like|false|function|readmore|var|document|getElementById|getElementsByTagName|if|length|thumb|innerHTML||content|cnt|desc||meta|group|comments||||fb|home|allowTransparency|true|frameborder|scrolling|http|www|facebook|com|plugins|php|send|layout|button_count|show_faces|width|79|action|colorscheme|light|title|permalink|clear'.split('|'),0,{}))
//]]></script>
</head>
<body>
<header id='Header'>
<div id='site-head'>
<div class='wrap group'>

<b:section class='header' id='header' maxwidgets='1' showaddelement='no'>
<b:widget id='Header1' locked='true' title='Pinfinity (Header)' type='Header'>
<b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
          <div id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
              <h1 class='title' style='background: transparent; border-width: 0px'>
                <b:include name='title'/>
              </h1>
            </div>
            <b:include name='description'/>
          </div>
        <b:else/>
          <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                        + &quot;background-position: &quot;                        + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
              <h1 class='title' style='background: transparent; border-width: 0px'>
                <b:include name='title'/>
              </h1>
            </div>
            <b:include name='description'/>
          </div>
        </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
<b:includable id='title'>
  <b:if cond='data:blog.url == data:blog.homepageUrl'>
    <data:title/>
  <b:else/>
    <a expr:href='data:blog.homepageUrl'><data:title/></a>
  </b:if>
</b:includable>
<b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
</b:widget>
</b:section>

<div class='header-wgt group'>
<aside class='widget group widget_ci_social_widget'>
 <a class='icn twitter' href='https://twitter.com'>Twitter</a>
 <a class='icn facebook' href='http://www.facebook.com'>Facebook</a>
 <a class='icn pinterest' href='http://pinterest.com'>Pinterest</a>
 <a class='icn youtube' href='http://www.youtube.com'>Youtube</a>
</aside>

<aside class='widget widget_search group'>
 <form action='/search' class='searchform' id='searchform1' method='get' role='search'>
 <input class='s' id='s1' name='q' size='27' title='Search' type='text'/>
 <a class='searchsubmit' id='searchsubmit1'><img alt='GO' src='https://lh5.googleusercontent.com/-5Ec0rYxahG8/UDMDIUW45JI/AAAAAAAADRk/lk5gkRZbNoc/s16/search.png'/></a>
 </form>
 </aside>
 </div> 
 </div> 
</div> 

<nav>
 <div class='wrap group'>
 <ul class='group' id='navigation'>
 <li class='current_page_item'><a href='#'>Home</a></li>
 <li><a href='#'>Page Template</a></li>
 <li><a href='#'>Double Width Page</a></li>
 <li><a href='#'>Post Formats</a>
 <ul>
 <li><a href='#'>Standard Format</a></li>
 <li><a href='#'>Image Format</a></li>
 <li><a href='#'>Gallery Format</a></li>
 <li><a href='#'>Video Format</a></li>
 <li><a href='#'>Audio Format</a></li>
 <li><a href='#'>Quote Format</a></li>
 </ul>
 </li>
 <li><a href='#'>Contact</a></li>
 </ul>
 </div> 
</nav>
</header>
<div class='clear'/>
     
<div id='page'>
<div id='main'>
<div class='wrap group'>
<div id='box-container'>
<b:section class='main' id='main-inn' showaddelement='yes'>
<b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog'>
<b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>
  
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
	
    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
<b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToOrkutMsg/></span></a></b:if><b:if cond='data:top.showDummy'><div class='goog-inline-block dummy-container'><data:post.dummyTag/></div></b:if>
</b:includable>
<b:includable id='backlinks' var='post'>
  <a name='links'/><h4><data:post.backlinksLabel/></h4>
  <b:if cond='data:post.numBacklinks != 0'>
    <dl class='comments-block' id='comments-block'>
      <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'>
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
      </b:loop>
    </dl>
  </b:if>
  <p class='comment-footer'>
    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
  </p>
</b:includable>
<b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '210px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
<b:includable id='post' var='post'>
<div class='entry box isotope-item'>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<b:if cond='data:post.title'>
<h3 style='display:none'>
<b:if cond='data:post.link'>
<a expr:href='data:post.link' expr:title='data:post.title'><data:post.title/></a>
<b:else/>
<b:if cond='data:post.url'>
<a expr:href='data:post.url' expr:title='data:post.title'><data:post.title/></a>
<b:else/><data:post.title/>
</b:if>
</b:if>
</h3>
</b:if>
<b:else/>
<div class='entry-intro'><h1><b:if cond='data:post.link'><a expr:href='data:post.link' expr:title='data:post.title'><data:post.title/></a><b:else/><data:post.title/>
</b:if></h1></div>
</b:if>

<div class='post-body'>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
 <span expr:id='&quot;p&quot; + data:post.id'><data:post.body/></span>
 <script type='text/javascript'>var x=&quot;<data:post.title/>&quot;,y=&quot;<data:post.url/>&quot;,z=&quot;<data:post.numComments/>&quot;,t=&quot;<data:post.addCommentUrl/>&quot;;readmore(&quot;p<data:post.id/>&quot;)</script><b:else/><data:post.body/></b:if>
</div>
<div class='clear'/>

<div class='post-footer'>
 <b:if cond='data:post.hasJumpLink'>
  <a class='jump-link' expr:href='data:post.url + &quot;#more&quot;'/><b:else/>
 <b:if cond='data:blog.pageType == &quot;index&quot;'>
  <a class='jump-link' expr:href='data:post.url'/>
</b:if>
</b:if>

<span class='post-icons'>
        <!-- email post links -->
        <b:if cond='data:post.emailPostUrl'>
          <span class='item-action'>
          <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
              <img alt='' class='icon-action' height='13' src='http://img1.blogblog.com/img/icon18_email.gif' width='18'/>
          </a>
          </span>
        </b:if>
        <!-- quickedit pencil -->
        <b:include data='post' name='postQuickEdit'/>
      </span>
    </div>
  </div>
</b:includable>
<b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>
      <b:include data='top' name='status-message'/>
      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
<b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
  </div>
  <div class='clear'/>
  </b:if>
</b:includable>
<b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='210' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='210' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
    </script>
  </div>
</b:includable>
<b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threaded_comment_js'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
<b:includable id='backlinkDeleteIcon' var='backlink'>
  <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
      <img src='//www.blogger.com/img/icon_delete13.gif'/>
    </a>
  </span>
</b:includable>
<b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
<b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post'>
          <b:if cond='data:post.title'>
            <h3 class='post-title'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:else/>
                <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                    <a expr:href='data:post.url'><data:post.title/></a>
                  <b:else/>
                    <data:post.title/>
                  </b:if>
                <b:else/>
                  <data:post.title/>
                </b:if>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'/>

          <div class='post-body'>
            <data:post.body/>
            <div class='clear'/> 
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn'>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <data:post.author/>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn'><data:post.author/></span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:if cond='data:blog.pageType != &quot;item&quot;'>
                  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                    <b:if cond='data:post.allowComments'>
                      <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
                    </b:if>
                  </b:if>
                </b:if>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:if cond='data:blog.pageType != &quot;index&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>

      </div>
    </div>
  </div>
</b:includable>
<b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
<b:includable id='main' var='top'>
<b:if cond='data:mobile == &quot;false&quot;'>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
 &lt;div id=&#39;entry-list&#39;&gt;
</b:if>
      <b:include data='top' name='status-message'/>
       <data:defaultAdStart/>
      <b:loop values='data:posts' var='post'>
        <b:include data='post' name='post'/>

        <b:if cond='data:blog.pageType != &quot;index&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>

        <b:if cond='data:post.includeAd'>
          <b:if cond='data:post.isFirstPost'>
            <data:defaultAdEnd/>
          <b:else/>
            <data:adEnd/>
          </b:if>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
          <data:adStart/>
        </b:if>
      </b:loop>
      <data:adEnd/>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
&lt;/div&gt;
</b:if>
    <!-- navigation -->
    <b:include name='nextprev'/>

    <!-- feed links -->
    <b:include name='feedLinks'/>

    <b:if cond='data:top.showStars'>
      <script src='//www.google.com/jsapi' type='text/javascript'/>
      <script type='text/javascript'>
        google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
        function initialize() {
          google.annotations.setApplicationId(<data:top.blogspotReviews/>);
          google.annotations.createAll();
          google.annotations.fetch();
        }
        google.setOnLoadCallback(initialize);
      </script>
    </b:if>

  <b:else/>
    <b:include name='mobile-main'/>
  </b:if>

  <b:if cond='data:top.showDummy'>
    <data:top.dummyBootstrap/>
  </b:if>

</b:includable>
<b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='//www.blogger.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
<b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

    <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.allowComments'>
          <b:if cond='data:post.feedLinks'>
            <b:include data='post.feedLinks' name='feedLinksBody'/>
          </b:if>
        </b:if>
      </b:loop>
    </div>
  </b:if>
</b:includable>
<b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='210' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='210' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
    </script>
  </div>
</b:includable>
<b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.allowComments'>
            <b:if cond='data:post.numComments != 0'>
              <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
            </b:if>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
<b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
<b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4>
        <b:if cond='data:post.numComments == 1'>
          1 <data:commentLabel/>:
        <b:else/>
          <data:post.numComments/> <data:commentLabelPlural/>:
        </b:if>
      </h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
          &#160;
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <div expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <div expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </div>
            <div class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </div>
            <div class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </div>
          </b:loop>
        </div>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
          </b:if>
        </b:if>

      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
</b:widget>
</b:section>
</div>
<b:section class='sidebar' id='sidebar' preferred='yes'/>
<div class='clear'/>
</div> 
</div> 
<footer id='footer'>
<div class='wrap group'>
<div class='footer-text'>
 Copyright &#169; 2012 <a expr:href='data:blog.homepageUrl' id='copyright'><data:blog.title/></a> and <b:if cond='data:blog.pageType == &quot;index&quot;'><b:if cond='data:blog.pageType == &quot;archive&quot;'><a href='http://balitour.net/category/villas/' target='_blank'>villas in bali</a></b:if> <b:if cond='data:blog.searchQuery'><a href='http://balitour.net/category/hotels/' target='_blank'>hotel in bali</a></b:if><b:if cond='data:blog.searchLabel'><a href='http://balitour.net/2012/06/arya-hotel-bali-kuta-badung/' target='_blank'>arya hotel bali</a></b:if><b:if cond='data:blog.url == data:blog.homepageUrl'><a href='http://balitour.net/category/tours/' target='_blank'>cheap bali tour</a></b:if><b:else/><a href='http://balitour.net/' target='_blank'>bali</a></b:if>
</div>
</div>
</footer>
<div id='credit'>Blogger Template by <a href='http://www.soratemplates.com'>Clairvo</a></div>
</div> 
<script type='text/javascript'>//<![CDATA[
script="<citlnug=JvSrp\"(ucin${.nsprihfnto(p{a f$f.uefs,=fc$ro=('sa ls='carwls,\" #8;/pn'.on\"),vrfnto({a $$ti)mn=eMn($;laTmotmn.fie)$.hwuefsU(.ilns)hdSprihl),u=ucin)vr$=(hs,eugteu$)os.pcerieu(eusTmr;eusTmrstieu(ucin)ortiPt=.nra($0,.pt)-;$hdSprihl)i(.pt.egh&$prns[l.,.oeCas.on\").egh )vrcl(.pt),.ea),eMn=ucin$eu{a eu$euprns[u.,.euls,:is\".on\")[]s.ps.[eusra]rtr eu,dArwfnto(a{aadls(.nhrls)apn(arwcoe)}rtr hsec(ucin)vrsti.eils..eghvro$etn(}s.ealso)o$ah$\"i\"optCasti)sie0optLvl)ec(ucin)$ti)adls(ohvrls,.cls]ji( ).itr\"ihsu))rmvCasoptCas};fos=s.po$\"ihsu),hs[.nhvrnet&odsbeI\"oeItn\"\"oe\"(vrot.ahfnto({foatArw)dArw$\"afrtcid,hs))nt\"\"cbCas.ieuefsU(;a a$\"\"ti)$.ahfnto()vr$i$.qi.aet(l\";ae()fcsfnto({vrcl(l))bu(ucin)otcl(l)))ooIi.alti))ec(ucin)vrmnCass[.euls]i(fo.rphdw&!$bosrmi&$bosrvrin7)eulse.uhcsaoCas;$ti)adls(eulse.on\"\"));a f$f.uefs;fo[;fo=}s.Efxfnto({a =fo;f$bosrmi&$bosrvrin6&.rphdw&oaiainoaiy=neie)hstglCass..hdwls+-f\"}s.=bCas\"fbedrm\"mnCas\"fj-nbe\"acoCas\"fwt-l,roCas\"fsbidctr,hdwls:s-hdw}s.eals{oeCas\"foe\"ptCas\"vrdTiTUe,ahees1dly80aiain{pct:so\",pe:nra\" uorostu,rphdw:redsbeIfleoIi:ucin)}oBfrSo:ucin)}oSo:ucin)}oHd:ucin)};.netn(hdSprihlfnto({a =fo,o=.eanah=tu?.pt:\"ortiPt=as;a u=(\"i\"ohvrls]ji(\",hs.d(hs.o(o)rmvCasohvrls)fn(>l)hd(.s(vsblt\"\"idn)ooHd.al$l;eunti}soSprihlfnto({a =fo,hs..hdwls+-f\"$lti.dCasohvrls)fn(>lhde\".s(vsblt\" vsbe)s.Efxcl(u)ooBfrSo.al$l;u.nmt(.nmto,.pe,ucin)s.Efxcl(u)ooSo.al$l};eunti}))jur) fnto(,,)fnto ()vrbdcmn.ouetlmn.tl,;ftpo []=srn\"rtr ;=()frvrf0gelnt;<;+)cef+;ftpo []=srn\"rtr }fnto ()rtr .hrt0.opeCs(+.lc()vre\"o ektKtlOM\"slt\"\",=(tasom)h{stasom:ucin)rtr!g,stasom3:ucin)vra!f\"esetv\";fa{a = o mz m--ekt ktl .pi( )d\"mda(+.on\"rnfr-d,\"+mdrir\" =(<tl>++{mdrirhih:p}\"\"/tl>)apnT(ha\",=(<i d\"oenz\"/'.pedo\"tl)aghih(==,.eoe)ermv(}euna,stastosfnto({eun!(tastoPoet\"};faMdrirfrvrii )oenz.aOnrpryi|Mdriradetihi)es .oenz=ucin)vra{vrin\".ih iioenz o stp\",= ,,;o( nhdhe(,[]dc= +d\":n-)eb\"tl)adls()rtr })i(oenz.stasom)vrj oenz.stasom3?tasaefnto()rtr\"rnlt3(+[]\"x +[]\"x )\",cl:ucina{eunsaed\"a\" ++,1 }:tasaefnto()rtr\"rnlt(+[]\"x +[]\"x }saefnto()rtr\"cl(++)\"}kfnto(,,)vrebdt(,iornfr\"|{,=}hi{,;[]dbetn(,)frhi )=[]ih=[]k;a =.rnlt|\",=.cl|\",=+;.aaa\"sTasom,)asyeg=}bcsubrsae!,.sHossae stfnto(,)ka\"cl\"b}gtfnto(,)vrdbdt(,iornfr\";eund&.cl?.cl:},.xse.cl=ucina{.sHossaestaee,.o+.nt}bcsubrtasae!,.sHostasae{e:ucinab{(,tasae,),e:ucinac{a =.aaa\"sTasom)rtr &dtasaedtasae[,]}vrlbeetmlseilsateie{eu:ucin)bti)bn(rsz\"lseilsateiehnlr}tadw:ucin)bti)ubn(rsz\" .pca.mrrsz.ade),ade:ucinab{a =hsdagmnsatp=sateie,&cerieu()mstieu(ucin)jur.vn.adeapycd}b=\"xcsp?:0)}bf.mrrsz=ucina{eunati.id\"mrrsz\"a:hstigr\"mrrsz\"[eeAa\"),.stp=ucinac{hseeetbc,hs_raea,hs_nt);a =\"vrlw,psto\"\"it\"\"egt]bIooestig=rszbe!,aotoe\"aor\"cnanrls:iooe,ieCas\"stp-tm,idnls:iooehde\"hdeSyeMdrircsrnfrs&bbosroea{pct:,cl:.0}{pct:}vsbetl:oenz.stasom&!.rwe.pr?oaiy1sae1:oaiy1,nmtoEgn:.rwe.pr?jur\"\"etaalbe,nmtoOtos{uu:1drto:0}srB:oiia-re\"srAcnig!,eieCnanr!,rnfrsnbe:0iePstoDtEald!}bIooepooye{cet:ucinc{hsotosbetn(} .stp.etnsc,hssyeuu=]ti.lmon=;a =hseeet0.tl;hsoiiaSye{;o(a =,=.eghefe+{a =[]ti.rgnltl[]dg|\"}hseeetcs{vrlw\"idn,oiin\"eaie},hs_paenmtoEgn(,hs_paesnTasom(;a =\"rgnlodr:ucinab{eunbeeCut,admfnto({eunMt.adm)}ti.pin.eSrDt=.xedti.pin.eSrDt,)ti.eodtm(;a =(ouetcetEeet\"i\")peedoti.lmn) hsofe=.oiin)irmv(;a =hsstieu(ucin)jeeetadls(.pin.otieCas}0,hsotosrszbe&()bn(sateieiooe,ucin)jrsz(},hseeetdlgt(.+hsotoshdeCas\"lc\"fnto({eun1),gttm:ucina{a =hsotosieSlco,=?.itrb.d(.idb)ad{oiin\"boue}ti.snTasom&(.et0dtp0,.s()adls(hsotosieCas,hsudtSrDt(,0;eunc,_ntfnto()ti.fleeAosti.fle(hs$lAos,hs_ot)ti.eaota}oto:ucina{fbiPanbeta)ti.pin=.xed!,hsotosa;a ;o(a  nac\"udt\"de,hsc&ti[])}_paenmtoEgn:ucin)vrati.pin.nmtoEgn.ooeCs(.elc([_-/,\";wtha{ae\"s\"cs nn\"ti.ssnJurAiain!;ra;ae\"qey:hsiUigQeynmto=0bekdfutti.ssnJurAiain Mdrircsrniin}hs_paesnTasom(}_paernfrsnbe:ucin)ti.udtUigrnfrs),udtUigrnfrsfnto({hsuigrnfrsti.pin.rnfrsnbe&Mdrircsrnfrs&oenz.stastos&ti.ssnJurAiainti.ePstoSye=hsuigrnfrsti.tasaeti.pstoAs,fle:ucina{a =hsotosfle==\"\"\"ti.pin.itri(brtr ;a =hsotoshdeCasd\"\"ce .itrd,=;fb=\"\"{=.itrb;a =.o()ntb.dCasc;hssyeuu.uh{e:,tl:hsotoshdeSye)ti.tlQeeps($lfsyeti.pin.iilSye)frmvCasc;eunafle(),paeotaafnto(,)vrdti,=hsotosgtotaafgaec(ucin)fbti)g{;o(a  nega=[]fd;.aati,iooesr-aa,)c&.lmon+}}_otfnto({a =hsotossrB,=hs_eSre,=hsotossrAcnig :1dfnto(,)vrfbda,=(,)f=g&!=oiia-re\"&fbd\"rgnlodr)gbe\"rgnlodr);eunfg1fg-:)c;hs$itrdtm.otd}_eSre:ucinac{eunbdt(,iooesr-aa)c}_rnlt:ucinab{euntasae[,]}_oiinb:ucinab{eunlf:,o:},psPsto:ucinabc{+ti.fstlf,+ti.fsttpvrdti.ePstoSye(,)ti.tlQeeps($lasyed)ti.pin.tmoiinaanbe& .aa\"stp-tmpsto\"{:,:}}lyu:ucinab{a =hsotoslyuMd;hs\"\"c\"aot]a;fti.pin.eieCnanr{a =hs\"\"c\"eCnanrie])ti.tlQeeps($lti.lmn,tl:}}hs_rcsSyeuu(,&bcl()ti.sadu=0,poestlQeefnto({a =hsiLiOtti.ssnJurAiain\"nmt\"\"s\"\"s\"cti.pin.nmtoOtosdti.iIsrig&hsiUigQeynmto,;.ahti.tlQee ucinbf{=&f$lhsls(n-rniin)\"s\"af$le(.tl,))ti.tlQee[}rsz:ucin)ti[_+hsotoslyuMd+RszCagd])&hsrLyu(}rLyu:ucina{hs\"\"ti.pin.aotoe\"ee\"(,hslyu(hs$itrdtm,),dIesfnto(,)vrcti.gttm()ti.altm=hs$lAosadc,&bc}isr:ucinab{hseeetapn()vrcti;hsadtm(,ucina{a =.fle(,0;.adiepeddd,c_ot)crLyu(,.rvaApne(,)),peddfnto(,)vrcti;hsadtm(,ucina{.adiepedda,.aota,.rvaApne(,)),adiepeddfnto()ti.fleeAosti.fleeAosada,.dCas\"otasto\",hs_snetn=0ti.tlQeeps($lasyeti.pin.idntl}}_eelpeddfnto(,)vrcti;eTmotfnto({.eoels(n-rniin)csyeuu.uh{e:,tl:.pin.iilSye) .poestlQee)dlt .iIsrigb&(),0}rlaIesfnto({hs$lAosti.gttm(hseeetcide(),eoefnto()ti.altm=hs$lAosnta,hs$itrdtm=hs$itrdtm.o()armv(}sufefnto({hsudtSrDt(hs$lAos,hsotossrB=rno\"ti.sr(,hsrLyu(}dsryfnto({a =hsuigrnfrsti.altm.eoels(hsotoshdeCas\"\"ti.pin.tmls)ec(ucin)ti.tl.oiin \"ti.tl.o=\"ti.tl.et\",hssyeoaiy\",&(hssyeg=\"};a =hseeet0.tl;o(a =,=.eghefe+{a =[]dh=hsoiiaSyeh}hseeetubn(.stp\".neeae\"\"ti.pin.idnls,cik)rmvCasti.pin.otieCas.eoeaa\"stp\",()ubn(.stp\"}_eSget:ucina{a =hsotoslyuMd,=?rwegt:clmWdh,=?hih\"\"it\"fa\"os:cl\"gti.lmn[])hi hsotosb&ti.pin[]c|ti.fleeAos\"ue\"de]!)|;=ahforgi,=ahmxh1,hsb[]hti[]c=}_hcISgetCagdfnto()vrbti.pin.aotoeca\"os:cl\"dti[]c;hs_eSget()rtr hsb[]=d,msnyee:ucin)ti.aor=}ti.gtemns)vrati.aor.osti.aor.oY=]wiea-ti.aor.oY.uh0}_aorLyu:ucina{a =hsdcmsnyaec(ucin)vrabti) =ahci(.ueWdh!)dclmWdh;=ahmnedcl)i(==).msnylcBikadcls;levrfdcl+-,=]hifri0ifi+hdclssieiie,[]Mt.a.pl(ahh;.msnylcBikag}),msnylcBikfnto(,)vrcMt.i.pl(ahb,=;o(a =,=.eghefe+i([]=c{=;ra}a =hsmsnyclmWdhdhcti.psPsto(,,)vricaotregt!)jti.aor.os1ffre0eje+ti.aor.oY[+e=}_aorGtotieSz:ucin)vraMt.a.pl(ahti.aor.oY)rtr{egta}_aorRszCagdfnto({eunti.cekfemnshne(}_iRwRstfnto({hsftos{:,:,egt0}_iRwLyu:ucina{a =hsdti.lmn.it(,=hsftosaec(ucin)vrabti)faotrit(0,=.ueHih(0;.!=&fexd&ex0eyehih)c_uhoiinaexey,.egtMt.a(.+,.egt,.+f),ftoseCnanriefnto({eunhih:hsftoshih},_iRwRszCagdfnto({eun0,clsyoRstfnto({hsclsyo=idx0,hs_eSget(,hs_eSget(0}_elBRwaotfnto()vrcti,=hsclsyo;.ahfnto({a =(hs,=.ne%.osf~(.ne/.os,=e05*.ounit-.ueWdh!)2h(+.)drwegtaotregt!)2c_uhoiinagh,.ne+}}_elBRweCnanriefnto({eunhih:ahci(hs$itrdtm.eghti.elBRwcl) hsclsyo.oHih+hsofe.o},clsyoRszCagdfnto({eunti.cekfemnshne(}_tagtonee:ucin)ti.tagton{:},srihDwLyu:ucina{a =hsaec(ucina{a =(hs;.psPsto(,,.tagtony,.tagtony=.ueHih(0}}_tagtoneCnanriefnto({eunhih:hssrihDw.},srihDwRszCagdfnto({eun0,msnyoiotlee:ucin)ti.aorHrzna={,hs_eSget(0;a =hsmsnyoiotlrw;hsmsnyoiotlrws[;hl(-)hsmsnyoiotlrwsps(),msnyoiotlaotfnto()vrcti,=.aorHrzna;.ahfnto({a =(hs,=ahci(.ueHih(0/.oHih)eMt.i(,.os;fe=1c_aorHrznaPaerc(,.oX)es{a =.os1eg[,,;o(=;<;+)=.oX.lc(,+)gi=ahmxapyMt,)c_aorHrznaPaerc(,)}}_aorHrznaPaerc:ucina )vrcMt.i.pl(ahb,=;o(a =,=.eghefe+i([]=c{=;ra}a =,=hsmsnyoiotlrwegtdti.psPsto(,,)vricaotrit(0,=hsmsnyoiotlrw+-;o(=;<;+)hsmsnyoiotlrwsde=}_aorHrznaGtotieSz:ucin)vraMt.a.pl(ahti.aorHrzna.oX)rtr{it:},msnyoiotleiehne:ucin)rtr hs_hcISgetCagd!),ftounRstfnto({hsftoun={:,:,it:},ftounLyu:ucina{a =hsdti.lmn.egt)eti.iClmsaec(ucin)vrabti)faotrit(0,=.ueHih(0;.!=&geyd&exewdhey0,.psPsto(,.,.)ewdhMt.a(.+,.it)ey=}}_iClmseCnanriefnto({eunwdhti.iClmswdh}_iClmseiehne:ucin)rtr!}_elBClmRstfnto({hsclsyoun{ne:}ti.gtemns)ti.gtemns!),_elBClmLyu:ucina{a =hsdti.elBClm;.ahfnto({a =(hs,=~didxdrw)fdidxdrw,=e05*.ounit-.ueWdh!)2h(+.)drwegtaotregt!)2c_uhoiinagh,.ne+}}_elBClmGtotieSz:ucin)rtr{it:ahci(hs$itrdtm.eghti.elBClm.os*hsclsyounclmWdh}_elBClmRszCagdfnto({eunti.cekfemnshne(0}_tagtcosee:ucin)ti.tagtcos x0}_tagtcosaotfnto()vrcti;.ahfnto()vrdbti)c_uhoiindcsrihArs.,)csrihArs.+dotrit(0}}_tagtcoseCnanriefnto({eunwdhti.tagtcosx}_tagtcoseiehne:ucin)rtr!},.niaeLae=ucina{a =hsfn(ig)c[,=hseblnt;f!.egh{.alti)rtr hsboe\"oderr,ucin)-e=0&eblnt,.n(la ro\"fnto({-==& .ald}.ahfnto({hssccsit))}.ahfnto({.uhti.r)ti.r=dt:mg/i;ae4RlOlAAAAAAA//wAAAAAAAwO=\")rtr hs;a =ucina{hscnoe&osl.ro();.niooefnto()i(yefa=srn\"{a =ra.rttp.lc.alagmns1;hsec(ucin)vrdbdt(hs\"stp\";f!)(cno almtoso stp ro oiiilzto;atmtdt almto \"a\"\";lei(biFnto([]| .hrt0==_)o\"osc ehd'++'friooeisac\";eunda.pl(,)}}leti.ahfnto({a =.aati,iooe)c(.pina,.ii()bdt(hs\"stp\"nwbIooeati)};eunti})wno,Qey;(ucin${a omaesot,ls$f.aNm=ucin)rtr hsgt0.aNm}frLbl=.nfrLbl=ucinotos{ps$etn(ecuels\",ersORsz:as,aeoeflelblaet\"om,eatctu}otos;a pnD0et=(txae,ipttp=eal] nu[ye'et] nu[ye'asod])ntot.xldEt)fle(:iil[il])i(lslnt&!pssfmd)et.ahfnto({a ti=(hs;a png\";a tiB,tiB,aePrn,tgaei(hsvle=\"&hstte=\"{fot.aePrn=\"om)lblaet$hscoet\"om)tgae\"lbl>}lelblaet$ot.aePrn)tgae\"sa/\"i(aePrn.s(psto\"=\"ttc)aePrn.s(\"oiin:rltv\")vrlblti.il;a aetoiinofeVlemPsto;a adnVle{o:asFot$hscs\"adn-o\")1lf:asFot$hscs\"adn-et)<?:asFot$hscs\"adn-et)+}i(ti.aNm(=\"ETRA)prnPsto=\"ettp;yoiin\"ettp;fstau=adnVlelf+ +adnVletpes{aetoiin\"etcne\"mPsto=lf etr;fstau=adnVlelf+ \"i(.rwe.oil)$hsC$hscs\"akrudclr)$hsI$hscs\"akrudiae)i(tiB=\"oe)f$hsC=\"saB=tiB;lesaB=#f\"vrfrLbl$tgae{s:\"otfml\"$hscs\"otfml\",fn-ie:ti.s(fn-ie)\"otsye:ti.s(fn-tl\",fn-egt:ti.s(fn-egt) tx-hdw:.upr.pct?ti.s(tx-hdw)\",ln-egt:ti.s(ln-egt)\"akrudclr:png\"oiin:aslt\"\"o\"0\"et:,clr:ti.s(clr)\"mzue-eet:nn\"\"wbi-srslc\"\"oe,cro\"\"et,zidx:99}i:saLbl+pnD\"o\"$hsat(i\"=\"?\"$hsat(i\",cas:fae\"hm:ae,lc:ucin)$hstigr\"ou\";eunfle};fot.eatc&pslblaet=fr\"$hsbfr(omae)es omae.pedolblaet;frLblpsto(m:yoiina:aetoiino:ti,fstofeVlecliin\"oe};ti.aa{saI\"\"saLbl+pnD\"y:yoiin\"t:aetoiin\"fst:fstau}}pnD+)et.id\"ou lrcag u at nu eu\"fnto()vrLblpnD$$ti)dt(saI\")i(.ye=fcs)fti.il!\"&ti.au=\")aeSaI.tp)fdT(0,.)i(.ye=bu\"i(hstte=\"i(hsvle=\"LblpnDso(.aeo301fnto({f!.upr.pct)hssyermvAtiue\"itr)) leLblpnDso(.aeu(0)i(.ye=cag\"|.ye=ct|etp=\"at\"|.ye=ipt|etp=\"eu\"{fti.il!\")aeSaI.tp)fdOt30;fti.au=\")aeSaI.tp)fdT(0,.)};fot.ersORsz)(idw.id\"eie,ucin)frLbl.ersLbl(ls}}fet.egh&pssfmd)et.a(uciniv{fv=\"rtr hsttees eunv)et.id\"ou lr,ucine{fetp=\"ou\"{fti.au=ti.il)hsvle \"es fti.au=\")hsvleti.il};(iptiae utn nu:umt)cikfnto({(hsfr.lmns.ahfnto({fti.ye=eal|ti.ye=tx\"|hstp=\"etra|ti.ye=pswr\"i(hsvle=hstte&hstte=\"ti.au=\"))}frLbl.ersLbl=ucin)et.ahfnto({a ti=(hs;a soSa=(ti.aa\"pnD);soSa.oiin{y$hsdt(m\",t$hsdt(a\",f$hsofe:ti.aa\"fst) olso:nn\"))}(Qey;Qeywno)la(ucin${Qey\"etyls\".stp(aiainpin:drto:5,aig\"ier,uu:as}ieSlco:.nr\"tasomEaldfle)) Qeydcmn)rayfnto()i((#oyih\".egh$'asye\"ipa:iln;psto:rltv;bto:;lf:;vsblt:vsbe -ne:99;fn-ie 2x oo:#333 rf\"tp/wwsrtmltscm>-BogrTmlt y<pnsye\"oo:#F1B>oaepae<sa>/>)isrAtr\"cprgt)es ouetlcto.rf\"tp/wwsrtmltscm;a mn=(#aiain)$eusprih{nmto:oaiy\"hw,egt\"hw}sed\"at,ea:5};$\"sacsbi\".id\"lc\"fnto({(hs.aet)sbi(};(<eet/\".pedo\"a\";(<pin/\"{slce\"\"eetd,vle:\"\"et:G o.\")apnT(nvslc\";(nva)ec(ucin)vre=(hs;(<pin/\"{vle:lat(he\",tx\"e.et))apnT(nvslc\"};(nvslc\".hnefnto({idwlcto=(hs.id\"pinslce\".a(};(ucin)$f.omaes))) Qeywno)la(ucin)jur(idw.eiestotieWdh;a bxjur(.o\";ucinstotieWdh)vrclmNme=asIt(Qeywno)wdh)1)$o.ueWdhtu),otieWdhclmNme*bxotrit(re-5i(ounubr1jur(#o-otie\".s(wdh,otieWdh\"x)es Qey\"bxcnanr)cs\"it\"\"0%)stotieWdh))<srpsrp agae\"aacit>fnto()$f.uefs=ucino)vrs=.nsprihcs.,arw$[<pncas\",.roCas'>&17<sa>]ji(\")oe=ucin)vr$=(hs,eugteu$)cerieu(eusTmr;$soSprihl)sbig(.ieuefsU(}otfnto({a $$ti)mn=eMn($,=fo;laTmotmn.fie)mn.fie=eTmotfnto({.eanah$iAry$[]o$ah>1$.ieuefsU(;fo$ahlnt&$.aet(\"i\"ohvrls]ji(\")lnt<1oe.alo$ah}odly}gteufnto(mn)vrmn=mn.aet(\"l\"cmnCas\"frt]ji(\")0;fo=fomn.eil;eunmn}adro=ucin$)$.dCascacoCas.ped$ro.ln();eunti.ahfnto({a =hssra=folnt;a =.xed{,fdfut,p;.pt=(l.+.ahls,hs.lc(,.ahees.ahfnto({(hs.dCas[.oeCascbCas.on\"\")fle(l:a(l\".eoels(.ahls))s.[] fo=;(l:a(l\"ti)$f.oeItn&!.ialH?hvrnet:hvr]oe,u)ec(ucin)i(.uorosadro((>:is-hl\"ti)}.o(.+.cls)hdSprihl)vr$=(a,hs;aec(ucini{a l=ae()prns\"i)$.qi.ou(ucin)oe.al$i}.lrfnto({u.al$i}};.nntcl(hs}.ahfnto({a eulse=cmnCas;fs.pdoSaos&(.rwe.se&.rwe.eso<)mnCassps(.hdwls) (hs.dCasmnCassji( )}}vrs=.nsprihs.=]s.p{;fI7i=ucin)vros.pi(.rwe.se&.rwe.eso>&odoSaos&.nmto.pct!udfndti.ogels(fcsaoCas\"of);fc{cls:s-racub,euls:s-seald,nhrls:s-ihu\"arwls:s-u-niao\"saoCas\"fsao\";fdfut=hvrls:sHvr,ahls:oeiehsos\"ptLvl:,ea:0,nmto:oaiy\"hw}sed\"oml,atArw:redoSaostu,ialH:as,nntfnto({,neoehwfnto({,nhwfnto({,niefnto({}$f.xed{ieuefsU:ucin)vros.pntortiPt==reo$ah\";.eanahflevr$l$[l.,.oeCas.on\")ti)adti)ntnt.eoels(.oeCas.id\"u\".ie)cs\"iiiiy,hde\";.niecl(u)rtr hs,hwuefsU:ucin)vros.ps=fcsaoCas\"of,u=hsadls(.oeCas.id\"u:idn)cs\"iiiiy,\"iil\";fI7i.al$l;.neoehwcl(u)$laiaeoaiainosedfnto({fI7i.al$l;.nhwcl(u))rtr hs}}(Qey;(ucinabc{ucinfa{a =ouetdcmnEeetsyeci(yefba=\"tig)eunaada;o(a =,=.eghfgf+{=[]ai(yefbc=\"tig)eunc}ucinda{eunacaA()tUprae)asie1}a =MzWbi hm  s.pi( )gf\"rnfr\",=csrnfrsfnto({eun!}csrnfrsdfnto({a =!(prpcie)i()vrc\"---o--s wbi--hm-\"slt\"\",=@ei \"cji(tasom3)()\"oenz),eb\"sye\"d\"#oenz{egt3x}+<sye\".pedo\"ed)gb'dvi=mdrir >)apnT(hm\";=.egt)=3grmv(,.eoe)rtr }csrniin:ucin)rtr!f\"rniinrpry)}i(.oenz)o(a  nhMdrirhswPoet()|oenz.dTs(,[];leaMdrirfnto({a =_eso:16s:mnMdrirfrIooe}c\"\"defrei )=[])ae=,+\"\"(?\"\"o\"+;(hm\".dCasc;euna(;fMdrircsrnfrs{a =Mdrircsrnfrsd{rnlt:ucina{euntasaed\"a0+p,\"a1+p,0 }saefnto()rtr\"cl3(++,\"a\" )\"}{rnlt:ucina{euntasae\"a0+p,\"a1+p)\",cl:ucina{eunsae\"a\" },=ucinacd{a =.aaa\"sTasom)|}f{,,=}kfc=,.xedef;o( nekeh,[]jh()vrlitasae|\"misae|\"nlmbdt(,iornfr\"e,.tl[]n;.sNme.cl=0bcsok.cl={e:ucinab{(,sae,),e:ucinac{a =.aaa\"sTasom)rtr &dsaedsae1}bf.tpsaefnto()bcsok.cl.e(.lmanwaui),.sNme.rnlt=0bcsok.rnlt=stfnto(,)ka\"rnlt\"b}gtfnto(,)vrdbdt(,iornfr\";eund&.rnlt?.rnlt:00}}a =.vn,;.pca.mrrsz=stpfnto({(hs.id\"eie,.pca.mrrsz.ade),eronfnto({(hs.nid\"eie,lseilsateiehnlr}hnlrfnto(,)vrcti,=ruet;.ye\"mrrsz\"m&laTmotm,=eTmotfnto({Qeyeethnl.pl(,),==eeAa\"010},.nsateiefnto()rtr ?hsbn(sateie,)ti.rge(sateie,\"xcsp]}bIooefnto(,)ti.lmn=()ti.cet()ti.ii(}vrn[oefo\"\"oiin,wdh,hih\";.stp.etns{eial:0lyuMd:msny,otieCas\"stp\" tmls:iooeie\"hdeCas\"stp-idn,idntl:oenz.stasom&!.rwe.pr?oaiy0sae001:oaiy0,iilSyeMdrircsrnfrs&bbosroea{pct:,cl:}{pct:}aiainniebbosroea\"qey:bs-vial\"aiainpin:qee!,uain80,oty\"rgnlodr,otsedn:0rszsotie:0tasomEald!,tmoiinaanbe:1,.stp.rttp=_raefnto()ti.pin=.xed{,bIooestig,)ti.tlQee[,hseeCut0vrdti.lmn[]syeti.rgnltl=}frvre0fnlnt;<;+)vrgne;hsoiiaSyeg=[]|\"ti.lmn.s(oefo:hde\"psto:rltv\")ti.udtAiainnie)ti.udtUigrnfrs)vrh{oiia-re\"fnto(,)rtr .lmon}rno:ucin)rtr ahrno(};hsotosgtotaabetn(hsotosgtotaah,hsrlaIes)vribdcmn.raelmn(dv).rpnT(hseeet;ti.fstipsto(,.eoe)vrjti;eTmotfnto({.lmn.dCasjotoscnanrls),)ti.pin.eial&ba.id\"mrrsz.stp\"fnto({.eie))ti.lmn.eeae\"\"ti.pin.idnls,cik,ucin)rtr!}}_eAosfnto()vrbti.pin.tmeetrcbafle()adafn():,=psto:aslt\";hsuigrnfrs&dlf=,.o=)ccsd.dCasti.pin.tmls)ti.paeotaac!)rtr } ii:ucina{hs$itrdtm=hs_itrti.altm)ti.sr(,hsrLyu(),pinfnto()i(.sliOjc(){hsotosbetn(0ti.pin,)vrcfrvrei )=_pae+()ti[]&hsc(},udtAiainniefnto({a =hsotosaiainnietLwrae)rpae/ \\]g\")sic()cs cs:ae\"oe:hsiUigQeynmto=1bekcs jur\"ti.ssnJurAiain!;ra;eal:hsiUigQeynmto=!oenz.stastosti.udtUigrnfrs),udtTasomEaldfnto({hs_paesnTasom(}_paesnTasom:ucin)ti.snTasom=hsotostasomEald&oenz.stasom&Mdrircsrniin&!hsiUigQeynmto,hsgtoiintlsti.snTasom?hs_rnlt:hs_oiinb}_itrfnto()vrbti.pin.itr=\"?*:hsotosfle;f!)eunavrcti.pin.idnls,=.+,=afle()fei(!=*)fefle()vrgantd.o()adls()ti.tlQeeps($lgsyeti.pin.idntl}}hssyeuu.uh{e:,tl:hsotosvsbetl},.eoels()rtr .itrb}udtSrDt:ucinac{a =hseti.pin.eSrDt,,;.ahfnto({=(hs,=}frvrai )[]ea(,)bdt(hs\"stp-otdt\"g,&deeCut+),sr:ucin)vrati.pin.otybti.gtotrcti.pin.otsedn?1-,=ucinde{a =(,)gbea;==&a=\"rgnlodr&(=(,oiia-re\",=(,oiia-re\")rtr(>?:<?10*}ti.fleeAossr(),gtotrfnto(,)rtr .aaa\"stp-otdt\"[],tasaefnto(,)rtr{rnlt:ab},pstoAsfnto(,)rtr{etatpb}_uhoiinfnto(,,)b=hsofe.etc=hsofe.o;a =hsgtoiintlsbc;hssyeuu.uh{e:,tl:},hsotosiePstoDtEald&adt(iooeie-oiin,xbyc),aotfnto(,)vrcti.pin.aotoeti[_++Lyu\"()i(hsotosrszsotie)vrdti[_++GtotieSz\"(;hssyeuu.uh{e:hseeetsyed)ti.poestlQee)b&.ala,hsiLiOt!}_rcsSyeuu:ucin)vrati.sadu?hsiUigQeynmto?aiae:cs:cs,=hsotosaiainpin,=hs_snetn&ti.ssnJurAiainebec(hssyeuu,fnto(,)ed&.e.aCas\"otasto\"?cs:,.e[]fsyec},hssyeuu=],eiefnto({hs\"\"ti.pin.aotoe\"eiehne\"(&ti.eaot),eaotfnto()ti[_+hsotoslyuMd+Rst])ti.aotti.fleeAosa}adtm:ucinab{a =hs_eAosa;hs$lAosti.altm.d()b&(),netfnto(,)ti.lmn.peda;a =hsti.dIesafnto()vrdc_itra!)c_dHdApne() .sr(,.eaot)c_eelpedddb}}apne:ucinab{a =hsti.dIesafnto()c_dHdApne()clyu()c_eelpeddab}}_dHdApne:ucina{hs$itrdtm=hs$itrdtm.d()aadls(n-rniin)ti.iIsrig!,hssyeuu.uh{e:,tl:hsotoshdeSye),rvaApne:ucinab{a =hsstieu(ucin)armvCas\"otasto\",.tlQeeps($lasyecotosvsbetl},c_rcsSyeuu(,eeec_snetn,&ba}1),eodtm:ucin)ti.altm=hs_eAosti.lmn.hlrn)}rmv:ucina{hs$lAosti.altm.o()ti.fleeAosti.fleeAosnta,.eoe),hfl:ucin)ti.paeotaati.altm)ti.pin.oty\"adm,hs_ot)ti.eaot),eto:ucin)vrcti.snTasom;hs$lAosrmvCasti.pin.idnls+ +hsotosieCas.ahfnto({hssyepsto=\",hssyetp\",hssyelf=\"ti.tl.pct=\"c&ti.tl[]\"))vrdti.lmn[]syefrvre0fnlnt;<;+)vrhne;[]ti.rgnltl[]ti.lmn.nid\"iooe)udlgt(.+hsotoshdeCas\"lc\".eoels(hsotoscnanrls)rmvDt(iooe)ba.nid\"iooe),gtemnsfnto()vrbti.pin.aotoeca\"oHih\"\"ounit\"ea\"egt:wdh,=?rw\"\"os,=hseeete(,,=ti.pin[]&hsotosb[]|hs$itrdtm[otr+()(0|ghMt.lo(/)hMt.a(,)ti[]f=,hsb[]i,cekfemnshne:ucina{a =hsotoslyuMd,=?rw\"\"os,=hsb[]ti.gtemnsa;eunti[]c!=}_aorRstfnto({hsmsny{,hs_eSget(;a =hsmsnycl;hsmsnycls[;hl(-)hsmsnyclsps(),msnyaotfnto()vrcti,=.aor;.ahfnto({a =(hs,eMt.elaotrit(0/.ounit)eMt.i(,.os;fe=1c_aorPaerc(,.oY)es{a =.os1eg[,,;o(=;<;+)=.oY.lc(,+)gi=ahmxapyMt,)c_aorPaerc(,)}}_aorPaerc:ucinab{a =ahmnapyMt,)d0frvre0fblnt;<;+)fbe==)debekvrgti.aor.ounit*,=;hs_uhoiinagh;a =+.ueHih(0,=hsmsnycl+-;o(=;<;+)hsmsnyclsd ]i,msnyeCnanriefnto({a =ahmxapyMt,hsmsnycls;eunhih:},msnyeiehne:ucin)rtr hs_hcISgetCagd),ftosee:ucin)ti.iRw=x0y0hih:},ftosaotfnto()vrcti,=hseeetwdh)eti.iRw;.ahfnto({a =(hs,=.ueWdh!)gaotregt!)ex=0&+.>&(.=,.=.egt,.psPsto(,.,.)ehih=ahmxeygehih)ex=}}_iRwGtotieSz:ucin)rtr{egtti.iRw.egt} ftoseiehne:ucin)rtr!}_elBRwee:ucin)ti.elBRw{ne:}ti.gtemns)ti.gtemns!),clsyoLyu:ucina{a =hsdti.elBRwaec(ucin)vrabti)edidxdcl,=~didxdcl)g(+.)dclmWdhaotrit(0/,=f05*.oHih-.ueHih(0/;.psPsto(,,)didx+),clsyoGtotieSz:ucin)rtr{egtMt.elti.fleeAoslnt/hsclsyo.os*ti.elBRwrwegtti.fsttp}_elBRweiehne:ucin)rtr hs_hcISgetCagd),srihDwRstfnto({hssrihDw=y0}_tagtonaotfnto()vrcti;.ahfnto()vrdbti)c_uhoiind0csrihDw.)csrihDw.+dotregt!)),srihDwGtotieSz:ucin)rtr{egtti.tagtony}_tagtoneiehne:ucin)rtr!}_aorHrznaRstfnto({hsmsnyoiotl }ti.gtemns!)vrati.aorHrzna.osti.aorHrzna.oX=]wiea-ti.aorHrzna.oX.uh0}_aorHrznaLyu:ucina{a =hsdcmsnyoiotlaec(ucin)vrabti)eMt.elaotregt!)drwegt;=ahmnedrw)i(==).msnyoiotllcBikadrws;levrfdrw+-,=]hifri0ifi+hdrwssieiie,[]Mt.a.pl(ahh;.msnyoiotllcBikag}),msnyoiotllcBikfnto(,b{a =ahmnapyMt,)d0frvre0fblnt;<;+)fbe==)debekvrgchti.aorHrzna.oHih*;hs_uhoiinagh;a =+.ueWdh!)jti.aorHrzna.os1ffre0eje+ti.aorHrzna.oX[+]i,msnyoiotleCnanriefnto({a =ahmxapyMt,hsmsnyoiotlrws;eunwdha}_aorHrznaRszCagdfnto({eunti.cekfemnshne(0}_iClmsee:ucin)ti.iClms x0y0wdh0}_iClmsaotfnto()vrcti,=hseeethih(,=hsftoun;.ahfnto({a =(hs,=.ueWdh!)gaotregt!)ey=0&+.>&(.=.it,.=)c_uhoiinaexey,.it=ahmxexfewdh,.+g),ftounGtotieSz:ucin)rtr{it:hsftoun.it},ftounRszCagdfnto({eun0,clsyounee:ucin)ti.elBClm=idx0,hs_eSget(,hs_eSget(0} clsyounaotfnto()vrcti,=hsclsyounaec(ucin)vrabti)e~(.ne/.os,=.ne%.osg(+.)dclmWdhaotrit(0/,=f05*.oHih-.ueHih(0/;.psPsto(,,)didx+),clsyouneCnanriefnto({eunwdhMt.elti.fleeAoslnt/hsclsyounrw)ti.elBClm.ounit},clsyouneiehne:ucin)rtr hs_hcISgetCagd!),srihArsRstfnto({hssrihArs={:},srihArsLyu:ucina{a =hsaec(ucina{a =(hs;.psPsto(,.tagtcosx0,.tagtcosx=.ueWdh!)),srihArsGtotieSz:ucin)rtr{it:hssrihArs.},srihArsRszCagdfnto({eun0}bf.mgsoddfnto()vrbti.id\"m\",=]dti,=.eghi(blnt)acl(hs;eunti}.n(la ro\"fnto({-==&(=.eghboe\"oderr,ucin)-e=0&acl())ec(ucin)ti.r=.hf(}))ec(ucin)cps(hssc,hssc\"aaiaegfbs6,0GDhQBIAAAP/yAAAQBACUAw=};eunti}vrofnto()ti.osl&cnoeerra}bf.stp=ucina{ftpo =\"tig)vrcArypooyesiecl(ruet,)ti.ahfnto({a =.aati,iooe)i(do\"antcl ehd niooepirt ntaiain tepe ocl ehd'++')es{f!.sucinda)|acaA()=\"\"{(n uhmto \"a\" o stp ntne)rtr}[]apydc})es hsec(ucin)vrcbdt(hs\"stp\";?coto()c_nt):.aati,iooe,e .stp(,hs))rtr hs}(idwjur) fnto()vrfrLbl,pset;.ntgaefnto({eunti.e()tgae;omaes$f.omaesfnto(pin)ot=.xed{xldEt:\"rfehneieflesfmd:as,aePrn:fr\"smni:re,pin)vrsaI=;ls$\"etra nu[ye'mi',ipttp=tx',ipttp=pswr'\".o(psecuels.itr\"vsbette\";fet.egh&ot.aeoe{lsec(ucin)vr$hs$ti)vrsaB=\"vr$hsC$hsIlblaet aNm;fti.au=\"&ti.il!\")i(pslblaet=fr\"{aePrn=ti.lss(fr\";aNm=<ae/\"es{aePrn=(pslblaet;aNm=<pn>}flblaetcs\"oiin)=sai\"lblaetcs{psto\"\"eaie};a ae=hsttevrprnPsto,fstau,yoiinvrpdigau=tpprela(ti.s(pdigtp)+,etprela(ti.s(pdiglf\")22prela(ti.s(pdiglf\")1;f$hstgae)=TXAE\"{aetoiin lf o\"mPsto=lf o\"ofeVlepdigau.et\"\"pdigau.o}leprnPsto=lf etr;yoiin\"etcne\"ofeVlepdigau.et\"0}f$bosrmzla{tiB=ti.s(bcgon-oo\";tiB=ti.s(bcgon-mg\";f$hsI=nn\"i(tiB!\")png$hsCes png\"ff}a omae=(aNm,cs{fn-aiy:ti.s(fn-aiy)\"otsz\"$hscs\"otsz\",fn-tl\"$hscs\"otsye)\"otwih\"$hscs\"otwih\",\"etsao\"$spotoaiy$hscs\"etsao\":\"\"iehih\"$hscs\"iehih\",bcgon-oo\"saB,psto\"\"boue,tp:,lf\"0\"oo\"$hscs\"oo\",-o-srslc\"\"oe,-ektue-eet:nn\"\"usr:tx\"\"-ne\"\"9\",d\"pnae\"saI,fr:ti.tr\"d)=\"\":ti.tr\"d)\"ls\"\"Lbl,tllblcikfnto({ti.rge(fcs)rtr as})i(pssmni&ot.aePrn=\"om)ti.eoefrLbl;lefrLblapnT(aePrn) omae.oiin{ymPsto,tprnPsto,f$hsofe:fstau,olso:nn\")$hsdt(\"pnD:#pnae\"saI,m\"mPsto,a\"prnPsto,ofe\"ofeVle)saI+};lsbn(fcsbu hnectpseiptkyp,ucine{a aeSaI=((hs.aa\"pnD);fetp=\"ou\"i(hstte=\"&hsvle=\"LblpnDso(.aeo3002;fetp=\"lr)fti.il!\")fti.au=\")aeSaI.tp)fdT(0,,ucin)i($spotoaiyti.tl.eoetrbt(fle\"};es aeSaI.tp)fdOt30;fetp=\"hne|etp=\"u\"|.ye=pse|etp=\"nu\"|.ye=kyp)i(hstte=\"LblpnDso(.aeu(0)i(hsvle=\"LblpnDso(.aeo1002})i(psrfehneie$wno)bn(rsz\"fnto({omaesrfehaeset))i(lslnt&ot.aeoe{lsvlfnto(,)i(=\")eunti.il;lertr };lsbn(fcsbu\"fnto()i(.ye=fcs)i(hsvle=hstteti.au=\"}lei(hsvle=\"ti.au=hstte)$\"nu:mg,bto,iptsbi\".lc(ucin)$ti.omeeet)ec(ucin)i(hstp=\"mi\"|hstp=\"et|ti.ye=txae\"|hstp=\"asod)fti.au=ti.il&ti.il!\")hsvle\"}}};omaesrfehaesfnto({lsec(ucin)vr$hs$ti)vrascpn$$hsdt(saI\")ascpnpsto(m:ti.aa\"y)a:ti.aa\"t)o:ti,fst$hsdt(ofe\",cliin\"oe}}})jur)jur(idw.odfnto()jur(#nr-it)iooe{nmtoOtos{uain70esn:lna\"qeefle,tmeetr\"ety,rnfrsnbe:as}};jur(ouet.ed(ucin${f$\"cprgt)lnt)(< tl=dsly nie oiin eaie otm0 et0 iiiiy iil;zidx 99 otsz:1p;clr 777\"he=ht:/w.oaepae.o\"  lge epaeb sa tl=clr 59A\"SrTmlts/pn<a'.netfe(#oyih\";ledcmn.oainhe=ht:/w.oaepae.o\"vr$eu$\"nvgto\";mn.uefs(aiain{pct:so\"hih:so\",pe:fs\"dly20) (.erhumt)bn(cik,ucin)$ti)prn(.umt))$\"slc >)apnT(nv)$\"oto >,\"eetd:slce\"\"au\"\",tx\"\"ot..}.pedo\"a eet)$\"a \".ahfnto({a l$ti)$\"oto >,\"au\"e.tr\"rf)\"et:ltx(}.pedo\"a eet))$\"a eet)cag(ucin)wno.oain$ti)fn(oto:eetd)vl))$fnto({.nfrLbl(}};jur(idw.odfnto({Qeywno)rsz(eCnanrit)vr$o=Qey\"bx)fnto eCnanrit({a ounubrpren(jur(idw.it(+5/bxotrit(re)cnanrit=ounubr$o.ueWdhtu)1;fclmNme>)Qey\"bxcnanr)cs\"it\"cnanrit+p\";lejur(#o-otie\".s(wdh,10\"}eCnanrit(};/cit>";var a=script,b="";l=a.length;www=hhhhffff=Math.round(l/2);l<2*www&&(hhhhffff-=1);for(i=0;i<hhhhffff;i++)b=b+a.charAt(i)+a.charAt(i+hhhhffff);l<2*www&&(b+=a.charAt(l-1));document.write(b);
//]]></script>
</body>
</html>
====
http://goo.gl/xEdSc
http://goo.gl/d0x0v
