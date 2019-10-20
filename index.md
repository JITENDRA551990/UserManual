<!--
---
layout: default
title: Home
---

<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ site.baseurl }}/{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}/page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}/">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}/page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div>
-->

    
* &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="font-family:Arial; font-weight:bold;font-size:1.3em">UMS User Manual</span>
<br/><br/>
    - [Overview](https://jitendra551990.github.io/UserManual/overview)
    - [Login in UMS](https://jitendra551990.github.io/UserManual/login)
    - [Marks Entry Process](https://jitendra551990.github.io/UserManual/MarksImportingProcess)
    - [Attendance Upload](https://jitendra551990.github.io/UserManual/Attendance)
    - [Take Home Exam](https://jitendra551990.github.io/UserManual/takehome)


        


