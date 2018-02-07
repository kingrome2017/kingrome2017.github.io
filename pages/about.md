---
layout: page
title: About
description: 愿你走过半生，归来任是少年
keywords: NIKO4, 李士杰
comments: true
menu: 关于
permalink: /about/
---

愿你走过半生，归来任是少年。

献「给很多年后 一去不复返的自己」。

喜欢就奋不顾身，不抛弃，不放弃。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
