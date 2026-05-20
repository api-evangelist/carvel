---
title: "Signing imgpkg Bundles with cosign"
url: "https://carvel.dev/blog/signing-imgpkg-bundles-with-cosign/"
date: "Thu, 07 Oct 2021 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
imgpkg and cosign ¶ Some of y’all might remember the beginning of every DVD movie showing this warning (read: scare tactic) to try and combat piracy. These days, however, based on the amount of security breaches, dev tools could use a similar warning, i.e. using an image that hasn’t had its signature verified. “You wouldn’t insert a USB found on the sidewalk” Imgpkg is a way to package and distribute multiple images via a single OCI artifact known as a Bundle.
