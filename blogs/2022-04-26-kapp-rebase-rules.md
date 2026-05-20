---
title: "kapp rebase rules"
url: "https://carvel.dev/blog/kapp-rebase-rules/"
date: "Tue, 26 Apr 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
Who ¶This article could be helpful for anyone who runs kapp deploy -a …, but especially for people who wonder if kapp is capable of preserving some fields in a resource on the cluster during an update. Why ¶Here’s one example of a recent question in #carvel, our community channel in the Kubernetes Slack: Is there a way to use an annotation for kapp to somehow ignore immutable fields? […] somehow get the immutable field current values and pull them into the patch we are applying with kapp?
