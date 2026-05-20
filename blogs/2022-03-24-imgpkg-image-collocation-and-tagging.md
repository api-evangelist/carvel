---
title: "imgpkg image collocation and tagging"
url: "https://carvel.dev/blog/imgpkg-image-collocation-and-tagging/"
date: "Thu, 24 Mar 2022 00:00:00 +0000"
author: ""
feed_url: "https://carvel.dev/blog/index.xml"
---
imgpkg image collocation and tagging ¶Some people have been asking questions like “Why are all bundle images copied to the same repository?” “Why do I have so many tags in my repositories?” We will try to give an overview of how imgpkg works and try to answer these questions at the same time. Common terms ¶But before we can do this, lets try to establish some common terms OCI: Open Container Initiative, the official website Image: content stored within OCI registry Bundle: OCI Image that contains configuration and OCI images OCI Terminology Creating a Bundle and pushing it to the registry ¶A…
