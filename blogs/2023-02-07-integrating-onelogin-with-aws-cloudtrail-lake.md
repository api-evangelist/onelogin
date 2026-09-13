---
title: "Integrating OneLogin with AWS CloudTrail Lake"
url: "https://developers.onelogin.com/blog/aws-cloudtrail-lake/"
date: "2023-02-07"
author: "Unknown"
feed_url: "https://developers.onelogin.com/atom.xml"
---
One Identity is an integration partner with the new CloudTrail Lake service from Amazon Web Services (AWS). When OneLogin users generate activity within our platform, OneLogin can send event data via a predefined webhook to AWS EventBridge, which then triggers a lambda rule to store the event log in CloudTrail Lake. In this blog post, I’ll walk you through how to create this integration between your One Identity OneLogin tenant and AWS CloudTrail Lake.
