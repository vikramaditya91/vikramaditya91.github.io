---
layout: page
title: Crypto Updates
permalink: /crypto_update/
---

This is a simple blog which identifies the most oversold coins in the Binance market.
The basic idea is:
1. Identify the oversold coin
2. Put a sell-order for 5% increase of the coin value
3. If the coin does not reach the target, sell it at whatever it's current value is
<div class="posts">
  {% for post in site.categories.crypto %}
    	<article class="post">
      		<h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
      	<div class="entry">
        	{{ post.excerpt }}
      	</div>
      		<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    	</article>
  {% endfor %}
</div>

