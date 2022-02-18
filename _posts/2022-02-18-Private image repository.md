---
title: "Private image repository"
tags:
  - CI/CD
  - docker
  - image
  - artifactory

toc: true
---

# 1 What is private image repository

- Basically image repository for docker is 'docker hub'
- But it is public repository. So, for the company that wants to own private repository need use other repository.


# 2 What kind of private image repository exist now?

{% capture fig_img %}
![Foo]({{ '/assets/images/docker-registry.png' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>
  The gray background-colored are not the open-source project. From : https://landscape.cncf.io/?zoom=200</figcaption>
</figure>
