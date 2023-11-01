~~IN THEORY, I SHOULD JUST BE ABLE TO POST ANYTHING AS LONG AS IT'S MD OR HTML, RIGHT?~~\
ABSOLUTELY I CAN. NICE.

***

- GUIDES
  - [HONKAI: STAR RAIL PRO CONTROLLER](/guides/HSRPC/how)
 
***

<ul>
  {% for post in site.posts %}
    <li>POSTS</li>
    <ul>
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a> by {{ post.author }}
      </li>
    </ul>
  {% endfor %}
</ul>
