---
layout: post
title: "Userscript for Labelling Completed Qwiklabs"
date: 2019-09-01
tags: Qwiklabs Userscript
---

[Qwiklabs](https://www.qwiklabs.com) is a great online self-paced learning platform for getting hands-on experience of Google Cloud Platform. It has over 400 hands-on labs and quests for learn and practice.

As a Qwiklabs user, I figure out it is messy and damp to lookup unenrolled quests or incompleted labs from the Qwiklabs Catalog page or Search Results (https://www.qwiklabs.com/catalog). I desired to make a straight-forward way to idenify the catalog items, by adding a green check-circle next to those completed. So, I tried to develop a solution named "[Qwiklabs Complete Indicator](https://github.com/chriskyfung/qwiklabs-complete-indicator)".

<br>

The objectives of this project are:
- To develop a handy way to implement the enhancement to Qwiklabs website in a web browser.
- To indicate completed labs and quests in Qwiklabs Catalog pages, thereby easier to inspect the self-learning progress and look for unenrolled quests or incompleted labs.
- To design a location to store and update the name list of the completed items.

<br>

A prototype was developed using Tampermonkey <i class="fa fa-plug"></i> for Google Chrome <i class="fa fa-chrome"></i>. Tampermonkey is a Chrome extension which allows users easily create, edit and execute Javascript-based <i class="fa fa-code"></i> userscripts in the web browser. With the prototyped userscript, you can visually idenify the completed catalog items. A green check-circle (<i class="fa fa-check-circle" style="color:green"></i>) shows at the end of a lab or quest title that is stored within the list of completed records. A demo screenshot is shown below.

![demo image](https://github.com/chriskyfung/qwiklabs-complete-indicator/raw/master/demo-image.png)

For more information, you can visit in my GitHub repository <i class="fa fa-github"></i> ([chriskyfung/qwiklabs-complete-indicator](https://github.com/chriskyfung/qwiklabs-complete-indicator)).