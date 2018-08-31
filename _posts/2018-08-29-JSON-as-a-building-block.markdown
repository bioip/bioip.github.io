---
layout: post
title:  "JSON as a building block"
date:   2018-08-28 14:37:06 -0500
categories: [howto, semantics]
---

Once interfaces are prototyped and it is time to build them it useful to have a seperated layer in your application that serves the data that feeds into them. Seperation of the data serving from the web-interface 1) lets other independant or unrelated interfaces or applications to also be built against the response; 2) permits exposure of the data to script-based tools, i.e. where most analysis happens; and 3) lets a collaborating team focus on different areas of the application at the same time, for example one person can work on the data modelling, another on the UI/UX. 

![A JSON response for a Protonym in TaxonWorks]({{ "/assets/img/JSON.png" | absolute_url }})


