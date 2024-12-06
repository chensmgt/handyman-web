# My Project
Trying to build a new web for R&M.
# My Interest
I'm interested in new things.
# My Blog
Blog my journey on GitHub.com
{% for post in site.posts %}
    {% if post.next %}
        {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
        {% capture next_year %}{{ post.next.date | date: '%Y' }}{% endcapture %}
        {% if year != next_year %}
            </ul>
            <h2>{{ post.date | date: '%Y' }}</h2>
            <ul>
        {% endif %}
    {% else %}
        <h2>{{ post.date | date: '%Y' }}</h2>
        <ul>
    {% endif %}
    <li>
        <span>{{ post.date | date:"%b" }}</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
# Get in Touch
<ul>
<li><a href="https://github.com/{{ site.github_chensmgt }}">GitHub</a></li>
<li><a href="https://chensmgt.com/{{ site.coffecup_www.chensmgt.com }}">www.chensmgt.com</a></li>  
</ul>
