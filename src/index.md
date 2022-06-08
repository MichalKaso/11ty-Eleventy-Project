<link rel="stylesheet" href="/style.css"/>
(1)
--------
layout: base
--------

# Mike's *mk1EleventyWebsite*

{% for post in collections.posts %}
- [{{ post.data.title }}]({{ post.url }})
{% endfor %}

<hr/>
<small>A website by {{ site.author }} - &copy; {{ site.copyrightYear }}</small>
