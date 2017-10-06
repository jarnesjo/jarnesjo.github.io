## Trying out Github pages

We have a local hack, #codemodekalmar, hosted at [Webready HQ](https://webready.se) in Kalmar.

Trying to find this stuff out.

{% for post in site.posts %}	
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} .</small></p>			
{% endfor %}	
