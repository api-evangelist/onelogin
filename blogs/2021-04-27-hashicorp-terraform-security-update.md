---
title: "HashiCorp Terraform Security Update"
url: "https://developers.onelogin.com/blog/hashicorp-security-update/"
date: "2021-04-27"
author: "Unknown"
feed_url: "https://developers.onelogin.com/atom.xml"
---
Recommended Actions - Update your Terraform and CodeCov software ASAP Synopsis Late last week it was brought to our attention that CodeCov suffered an attack in which attackers gained access to their bash uploader script and modified it without CodeCov’s permission. This enabled hackers to modify the script and monitor data as it was uploaded to CodeCov including secrets, that were used in the CI pipeline. HashiCorp uses CodeCov’s uploader and as a result, their GPG signing key was exposed.
