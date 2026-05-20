---
title: "Updating resources automatically when their referenced resources are updated"
url: "https://carvel.dev/blog/updating-resources-automatically-when-their-referenced-resources-are-updated/"
date: "Thu, 30 Jun 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
Have you ever wanted your deployments or pods to automatically get redeployed when their referenced ConfigMaps or secrets are updated? In this blog, we are going to learn how to use kapp to re-start or re-deploy the resources when their referenced resources get updated. Deploy resources where one resource is being referenced by other ¶Let’s consider a ConfigMap and a deployment, where the ConfigMap is being referenced by the deployment.
