---
title: Microsoft Learn - Copilot Exercises
permalink: index.html
layout: home
---

# Work Smarter with AI

These hands-on exercises are designed to support training content on [Microsoft Learn](https://learn.microsoft.com/training/paths/work-smarter-with-ai/).

To complete the exercise, you'll need <u>either</u>:

- [Microsoft Copilot Pro or a Microsoft 365 account that includes Microsoft 365 Copilot](https://www.microsoft.com/microsoft-365/copilot#Gettingstarted)

    or

- A personal [Microsoft account](https://signup.live.com/) and [Microsoft Edge](https://www.microsoft.com/edge/download)

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions'" %}
| Exercises |
| ------- | 
{% for activity in labs  %}| [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}