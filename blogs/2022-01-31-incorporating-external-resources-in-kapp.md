---
title: "Incorporating external resources in kapp"
url: "https://carvel.dev/blog/incorporating-external-resources-in-kapp/"
date: "Mon, 31 Jan 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
kapp CLI encourages Kubernetes users to manage resources in bulk by working with “Kubernetes applications” (sets of resources with the same label). But there are often times when we want to incorporate resources that are not actually part of the same application (created by external agents). In this blog, we are going to learn how to use the kapp.k14s.io/exists annotation to wait for resources that are not owned by kapp.
