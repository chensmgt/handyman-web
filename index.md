# My Project
Trying to build a new web for R&M.
# My Interest
I'm interested in new things.
# My Blog
Blog my journey on GitHub.com
<ul>
  {% for post in site.post %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}post</a>
  </li>
  {% endfor %}
</ul>
# Get in Touch
<ul>
<li><a href="https://github.com/{{ site.github_chensmgt }}">GitHub</a></li>
<li><a href="https://chensmgt.com/{{ site.coffecup_www.chensmgt.com }}">www.chensmgt.com</a></li>  
</ul>
