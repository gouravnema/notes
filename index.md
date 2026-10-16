# Gourav's Notes 

This site is collection of my published notes. Here I will be logging and sharing my learning and knowledge around things/topics of my interests. 


## Posts
{% for post in site.posts %}
- [{{ post.title }}](/notes/{{post.url }}) - *{{ post.date | date: "%B %d, %Y" }}* {{ post.excerpt | strip_html | truncatewords: 30 }} 
{% endfor %}


## Reading Notes
List of my understanding from the books etc, I am reading/read. 

1.  [Surrounded by idiots](reading_notes/surrounded_by_idiots) *By Thomas Erikson*


## Tech Notes
