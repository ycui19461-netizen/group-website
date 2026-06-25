---
layout: home
lesson-example: "https://carpentries.github.io/lesson-example/"
title: Building Website in GitHub
---
 
{% include navigation.html %}
 
# Building website in GitHub

## Description
{{ site.description }}
{% assign lead=site.team——member | where: "role", "project lead"| first %}
{{ lead.name }}

More details about the project availaible from  the [About page](about.md)

See some [examples of our work]({{ page.lesson-example }}).

Have any questions about what we do? [We'd love to hear from you!](mailto: {{site.email}})

{% include footer.html %}
