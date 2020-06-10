---
title: Status Update 2020-06-08
tags: status
author: Mark Maglana
---

Vlad and I have been able to successfully integrate Prometheus and AlertManager
the past week via simple relations. Most notably we've achieved the following:
<!--more-->

1. Prometheus is able to detect the health of AlertManger instances long
   after the relation is established. It will then add or remove these
   AlertManager instances as needed without any human intervention

1. We have moved our repositories to a GitHub organization to make it
   more official: [https://github.com/charmed-lma](https://github.com/charmed-lma)

1. We have created a static website where we will be moving common README
   content such as prepping one's development environment and troubleshooting.
   See [https://charmed-lma.github.io](https://charmed-lma.github.io).
   This will also be the place for future status updates.

1. We're moving our project tracking to Jira after the fine folks at
   [Atlassian](https://www.atlassian.com) granted us an Open Source License
   for [charmed-lma.atlassian.net](https://charmed-lma.atlassian.net/jira/software/projects/LMA/boards/4/roadmap).
   Expect more news coming out about this migration.

There are still a few things down the pike that will need to be addressed
but we are hard at work organizing these tasks and addressing them as needed.

As of today, the project progress is as follows:

<a href="/assets/img/burnup-charts/2020-06-08.png">
![Burnup Chart 2020-06-08](/assets/img/burnup-charts/2020-06-08.png)
</a>
