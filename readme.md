# Introduction
CSCI3251 project, we assgined the lastest unsolved task to one joined the team.

# Code
```C
//c code
{% include_relative code.c %}
```
![example workflow](https://github.com/csci3251-2022/project-team-d/actions/workflows/c-cpp.yml/badge.svg)


# Contributors

| Task  | Contributor  |
| --- | --- |
| Task1 | FangFF |
| Task2 | ZTREvenstar |
| Task3 | AsonJtsz |
| Task4 | AppleLam (assigned) |
| Task5 | DanielASR (assigned) |
| Task6 | SteveTangO (assigned) |
| Task7 | baamdoo |

{% for stu in site.stu %}
  <h2>{{ stu.image }} - {{ stu.user }} - {{ stu.name }}</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}

Last updated: {{ site.time }}
