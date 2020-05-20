---
layout: page
title: Crypto History
permalink: /crypto_history/
---
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-103831149-5"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-103831149-5');
</script>
<div class="posts">
  {% for post in site.categories.crypto%}
    	<article class="post">
      		<h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
      	<div class="entry">
        	{{ post.excerpt }}
      	</div>
      		<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    	</article>
  {% endfor %}
</div>

