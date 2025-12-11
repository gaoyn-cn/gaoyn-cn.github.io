[首页](/) | [关于](/about)

# Notes

<ul>
 {% for post in site.posts %}
  <li>
    <a href="{{  post.url }}"> {{post.title}}  </a> - {{ post.date | date:"%Y-%m-%d"}}
  </li>
 {% endfor %}
</ul>
