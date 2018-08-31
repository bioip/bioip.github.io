---
layout: post
title:  "Edit taxon name"
date:   2018-08-28 14:37:06 -0500
categories: [interfaces, semantics]
---

While relatively clean and straightforward looking we spent a lot of time adding "intelligence" to our core nomenclatural ediging form. It included the first integration with the radial annotor, among other things. Behind the form are a series of JSON serving queries, and the NOMEN ontology. Our goal was to hide away the complexity of a graph-based nomenclature representation that referenced an ontology from the user.

![As ultimately implemented in TaxonWork]({{ "/assets/img/edit_taxon_name.png" | absolute_url }})
