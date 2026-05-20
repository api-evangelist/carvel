---
title: "Carvelizing Helm Chart"
url: "https://carvel.dev/blog/carvelize-helm-chart/"
date: "Wed, 16 Feb 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
In this blog post we will first show you how to wrap and distribute Bitnami Nginx Helm chart as a Carvel package, and then install it on the Kubernetes cluster via PackageInstall CR (via kapp-controller). Why should I choose Carvel ¶Kubernetes configuration takes many forms – plain YAML configurations, Helm charts, ytt templates, jsonnet templates, etc. Software running on Kubernetes lives in many different places, e.g. a Git repository, an archive over HTTP, a Helm repository.
