---
title: "Continuous delivery using a Carvel ytt Argo CD plugin"
url: "https://carvel.dev/blog/argocd-carvel-plugin/"
date: "Wed, 23 Feb 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
Argo CD is a declarative, GitOps, continuous delivery tool for Kubernetes. It’s design embraces GitOps philosophy of using Git as a single source of truth for the desired state of the system. In this example we’re storing desired application state in ytt templates, and extending Argo CD to template and deploy them.
