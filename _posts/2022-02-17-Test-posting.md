---
title: "Agile methodology - Scrum"
categories:
  - Agile
tags:
  - scrum
  - agile
---

### Agile

* Agile Methodology or Manifesto has emerged by 17 people in Snowbird, Utah.


### Scrum

* Scrum is one of the ways to implement agile.

* iterative philosophy : iterate over the changes and deployments for software developments (Plan - Build - Test - Review)


* Product Owner(Manager) who holds the responsibility to make sure that the application is being deployed and build as planned.

* Scrum Master(Team Leader) : handles day-to-day operations, running the meetings, handling the tasks

* Developer, Tester etc(Teammates)


{% capture fig_img %}
![Foo]({{ '/assets/images/scrum-sprint.png' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Scrum at a glance</figcaption>
</figure>



### Ordered -- Unordered -- Ordered

1. ordered item
2. ordered item
  * **unordered**
  * **unordered**
    1. ordered item
    2. ordered item
3. ordered item
4. ordered item

### Ordered -- Unordered -- Unordered

1. ordered item
2. ordered item
  * **unordered**
  * **unordered**
    * unordered item
    * unordered item
3. ordered item
4. ordered item

### Unordered -- Ordered -- Unordered

* unordered item
* unordered item
  1. ordered
  2. ordered
    * unordered item
    * unordered item
* unordered item
* unordered item

### Unordered -- Unordered -- Ordered

* unordered item
* unordered item
  * unordered
  * unordered
    1. **ordered item**
    2. **ordered item**
* unordered item
* unordered item

### Task Lists

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
  - [ ] Follow discussions
  - [x] Push new commits
