---
title: "The Hidden Costs of Misconfiguration"
url: "https://carvel.dev/blog/ytt-validations-released/"
date: "Tue, 27 Sep 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
A Cryptic Error ¶Take a look at this error message: ... Updating resource service/petc (serving.knative.dev/v1) API server says: admission webhook "validation.webhook.serving.knative.dev" denied the request: validation failed: "PORT" is a reserved environment variable: spec.template.spec.containers[0].env[0].name ... What you’re looking at is the tail end of a 30-minute circuitous journey locating and collecting logs after a particular service apparently failed to deploy. 🥵 The person trying to decipher this cryptic-to-them error message wasn’t versed in the intricacies of Knative services.
