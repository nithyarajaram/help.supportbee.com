---
layout: default
title: Contact Support Widget
description: How do setup the contact support widget
categories: widget
---

How do I put up the 'Contact Support' Widget on my website?
-----------------------------------------------------------

After logging in as an Admin,

1. Click on 'Admin' link in the top right of the scren
2. Select the 'Widget' tab
3. Select the position and language and copy the code 
4. Put it in your webpage below the </body> tag

How do I hide the 'Contact Support' tab and load the widget on clicking a link?
-------------------------------------------------------------------------------

If you don't want to use our 'Contact Support' tab, you have to edit the code and change position to none,

_position: none_

Then, on your webpage, put up a link (with the text that you want)

_&lt;a data-controls-modal='sb-overlay'&gt;Contact Us&lt;/a&gt;_

The data-controls-modal property bind the form to this link.
