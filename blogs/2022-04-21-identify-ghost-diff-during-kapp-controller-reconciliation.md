---
title: "Identify ghost diff during kapp Controller reconciliation"
url: "https://carvel.dev/blog/identify-ghost-diff-during-kapp-controller-reconciliation/"
date: "Thu, 21 Apr 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
kapp controller, a Package manager, is compatible with Gitops philosophy. It ensures that the cluster is or converging towards the desired state all the time. It achieve this by running the reconciliation loop after every syncPeriod duration.
