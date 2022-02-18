---
title: "git pull vs git fetch"
tags:
  - git

toc: true
---

# git pull vs git fetch

- In the simplest terms, git pull does a git fetch followed by a git merge.

## git pull

- A git pull is what you would do to bring a local branch up-to-date with its remote version, while also updating your other remote-tracking branches.

## git fetch

- You can do a git fetch at any time to update your remote-tracking branches under refs/remotes/<remote>/. This operation never changes any of your own local branches under refs/heads, and is safe to do without changing your working copy. I have even heard of people running git fetch periodically in a cron job in the background (although I wouldn't recommend doing this).


# source : https://stackoverflow.com/questions/292357/what-is-the-difference-between-git-pull-and-git-fetch
