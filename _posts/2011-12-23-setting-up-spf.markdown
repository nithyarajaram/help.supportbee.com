---
layout: default
title: Ensuring better email delivery with SPF records
description: How do setup SPF records 
categories: email.setup
---

What are SPF records? 
---------------------
SPF is an email validation system designed to prevent email spam. You can read more in the [Wikipedia entry on SPF](http://en.wikipedia.org/wiki/Sender_Policy_Framework). In short, to ensure better delivery of your email, you should allow SupportBee as a permitted sender by creating/updaing your SPF record. 

How do I create a SPF record allowing SupportBee as a permitted sender?
-----------------------------------------------------------------------
To create an SPF record for your domain:

1. Log in to the administrative console for your domain.
2. Locate the page from which you can update the DNS records. 
3. You may need to enable advanced settings.
4. Create a TXT record containing this text: _v=spf1 include:\_spf.supportbee.com ~all_
5. Publishing an SPF record that uses -all instead of ~all may result in delivery problems. 
6. Save your changes. 

Keep in mind that changes to DNS records may take up to 48 hours to propagate throughout the Internet. If you have difficulty creating an SPF record, contact your domain provider for assistance.
