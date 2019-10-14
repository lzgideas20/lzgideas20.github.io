# Hello World

## My Projects
Here is a list of projects that I am working on.

## My Interests
I'm interested in learning about coding and software development.

## My Blog
<!-- start of an unordered list -->
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{post.url}}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>

<!--Linking porject repo webpage and to a project repo-->
<ul>
<li>
<a href="https://lzgideas20.github.io/HelloWorld/" Hello World Project</a>
</li>
<li>
<a href="https://github.com/lzgideas20/HelloWorld" Hello World Repo </a>
</li>
</ul>
