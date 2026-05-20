---
title: "Migrate existing resources to a new kapp app"
url: "https://carvel.dev/blog/migrate-existing-resources-to-a-new-kapp-app/"
date: "Thu, 03 Mar 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
kapp CLI encourages Kubernetes users to manage resources in bulk by working with “Kubernetes applications” (a set of resources with the same label). But how do we manage resources already present on the cluster (created by kubectl apply or are part of another kapp app)? In this blog, we learn how to migrate from kubectl apply to a kapp app and move existing resources across kapp apps.
