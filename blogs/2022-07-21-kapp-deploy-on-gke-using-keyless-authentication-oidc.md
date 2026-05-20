---
title: "Kapp deploy on GKE using keyless authentication (OIDC)"
url: "https://carvel.dev/blog/kapp-deploy-oidc-gke/"
date: "Thu, 21 Jul 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
Who ¶This article can be helpful for anyone who wants to create the Github Action workflow to authenticate with GCP and to deploy Kubernetes manifest on GKE using kapp. Why ¶Earlier, we used to authenticate to Google Cloud from GitHub Actions by storing JSON service account key in GitHub Secrets. Now, that GitHub introduced OIDC tokens into GitHub Actions Workflows, you can authenticate from GitHub Actions to Google Cloud using OIDC (Workload Identity Federation), removing the need to export a long lived JSON service account key.
