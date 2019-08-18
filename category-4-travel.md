---
layout: page
title: reise
description: reise
header: \ reise
---

집떠나면 코가 반짝반짝 킁킁

proudly enjoy being a sincere and arduous Google Map Local Guide [Level 7](https://www.google.com/maps/contrib/100621312322588477431/reviews/@34.1858158,157.8809861,3z/data=!3m1!4b1!4m3!8m2!3m1!1e1)




해외편
* 대만 (upcoming)
* 독일어권에서의 제2안식 (upcoming)
* [Tokyo (2019)](/travel-tokyo)
* [Chiangmai (2018)](/travel-chiangmai) 
* [Shanghai (2018)](/travel-shanghai)
* [Trekking Alps and Swiss(2017)](/activity-alps)
* [Berlin (2016)](/travel-berlin)
* [Provence, France (2015)](/travel-provence)




국내편
* 부산
* 강릉
* 여수
* 제주



<!-- Posts -->
<ul id="posts">

	{% for post in paginator.posts %}

	  <li class="post">
	  	<h3><a href="{% if site.baseurl == "/" %}{{ post.url }}{% else %}{{ post.url | prepend: site.baseurl }}{% endif %}">{%if post.header %}{{ post.header }}{% else %}{{ post.title }}{% endif %}</a></h3>
      		
		 
	  </li>

    {% endfor %}

</ul>
