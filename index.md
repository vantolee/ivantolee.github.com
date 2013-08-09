---
layout: default
title: Vanto's Blog

---
{% include JB/setup %}

<div class="page-header">
  <h1>Hard word had make it easy.</h1>
</div>


<div class="row">
  <div class="span7">
    <ul class="posts">
      
      <li>
        <div class="title">
          <a href="/first-arrived-in-hangzhou.html">初到杭城</a>
          <time datetime="2013-03-23" class="pull-right">2013-03-23</time>
        </div>
        <div class="featurette">
          <div class="description pull-right">it's my loveit's my loveit's my loveit's my loveit's my loveit's my loveit's my loveit's my loveit's my loveit's my loveit's my loveit's my love</div>
          
          <img alt="初到杭城" src="http://pic.yupoo.com/fooleap_v/CJtzVqJn/small.jpg" class="thumbnail featurette-image pull-left">
          
          <a href="/first-arrived-in-hangzhou.html" class="more btn btn-mini pull-right">阅读更多</a>
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




