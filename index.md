Reasons My Code Is Broken
-------------------------

Personal blog for [Seán Kelleher](https://twitter.com/eZanmoto).

{% for post in site.posts %}
{{post.date|date_to_string}} &raquo; [{{post.title}}]({{post.url}})
{% endfor %}
