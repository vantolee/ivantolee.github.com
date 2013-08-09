---
layout: default
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

<div class="page-header">
  <h1>Hard work had make it easy!</h1>
</div>

<div class="row">
  <div class="span7">
    <ul class="posts">
      
      <li>
        <div class="title">
          <a href="/first-arrived-in-hangzhou.html" title="又到周末雨落时，手脚笨拙，表达能力较弱的我，也只能选择在这个时候，倾听雨声写写博客，显然有股小时写周记的味道，而思想心境却再也回不到过去。">初到杭城</a>
          <time class="pull-right" datetime="2013-03-23">2013-03-23</time>
        </div>
        <div class="featurette">
          <div class="description pull-right">又到周末雨落时，手脚笨拙，表达能力较弱的我，也只能选择在这个时候，倾听雨声写写博客，显然有股小时写周记的味道，而思想心境却再也回不到过去。</div>
          
          <img class="thumbnail featurette-image pull-left" src="http://pic.yupoo.com/fooleap_v/CJtzVqJn/small.jpg" alt="初到杭城">
          
          <a class="more btn btn-mini pull-right" href="/first-arrived-in-hangzhou.html">阅读全文</a>
        </div>
        <hr class="featurette-divider">
      </li>
      
     
      
    </ul>
   
  </div>
  

</div>

    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



