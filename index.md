Reasons My Code Is Hanging
--------------------------

Personal blog for [Seán Kelleher](https://twitter.com/eZanmoto).

I waste hours tracking down bugs, especially when my code doesn't have the decency to fail with an error and instead stays hanging in limbo. Documenting the bug makes it less of a waste. This is a bug report blog where I'll document things like the steps I went through to diagnose the bug, the root cause of the bug, the original failed assumptions that lead to the bug, ways of avoiding such bugs in the future, and similar ideas. It has the usual goals of documentation: to spread knowledge and prevent repeating mistakes, mainly for myself in six months' time..


{% for post in site.posts %}
{{post.date|date_to_string}} &raquo; [{{post.title}}]({{post.url}})
{% endfor %}
