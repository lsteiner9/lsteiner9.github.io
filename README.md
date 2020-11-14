## Introduction

Laura is an aspiring Java developer, as well as a professional violist, violinist, and music teacher. She recently graduated from UNM with a master's degree in music, and is currently attending the Deep Dive Coding Java + Android Bootcamp, gaining experience in Android app development.

### Current projects

* [Hello World: Java console application](https://github.com/lsteiner9/deep-dive-hello-world-ij)

* [Hello World: Android app](https://github.com/lsteiner9/hello-world)

### Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}


## Links

* [LinkedIn](https://www.linkedin.com/in/laurasteinerviola/)

* [YouTube](https://www.youtube.com/channel/UCeUSKKE-TqScB49RpeZuAQA)

* [Music website](https://lsteiner98.wixsite.com/website)
