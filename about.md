---
layout: page
title: About
permalink: /about/
---

As we wrapped up the official duration of a recent NSF grant we needed a place to index and/or store the various outcomes of the project.  As it was an "Innovation" based grant, some products were truly open ended, it felt like they should none-the-less get referenced somewhere.

This is an experimental use of a [commonly used blog generator too](https://jekyllrb.com/) to index the products of an NSF grant, in this case _ABI-1356515: "Collaborative Research: ABI Innovation: Rapid prototyping of semantic enhancements to biodiversity informatics platforms"_. 

We generated a DOI for this archive: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1409244.svg)](https://doi.org/10.5281/zenodo.1409244). See [how](https://guides.github.com/activities/citable-code/) using [Zenodo](https://zenodo.org).

# How does it work?  

Each post is links to a product, outcome, or observation dervied in whole or in part from the grant.  

_You can download this repository/archive, perhaps to re-archive the content, using [git](https://git-scm.com/), it's found on almost every computer by default. From a terminal just enter the command `git clone https://github.com/bioip/bioip.github.io.git`._

# Why this format?

Grants like those in the ABI Innovation program are perhaps never truly done, or at minimum there are some pieces that are complete, and some that are not.  A challenge is to index the state of the grant, for reporting and other purposes (like archiving), making the bits and pieces available for future use.  Some bits are big (e.g. large presentations or graphics, Google Drive directories) and don't naturally fit in finalized archives like [JOSS](https://joss.theoj.org/). Interfaces, and ideas for interfaces evolve over time, they may exist as [issue tracker issues](https://github.com/SpeciesFileGroup/taxonworks/issues) or [wireframe prototypes](https://www.invisionapp.com/). There are several other goals at work:

* Git and sites like Github lets us collaboratively edit the posts
* Git repos let others pull down the whole of the "results" by cloning the repository
* Git repos let others see how the results being presented change over time ("diffs" of prior commits)
* Git based projects are readily hosted on major public platforms
* Existing software tools let you produce websites that hosting platforms will automatically turn into websites (like this one) 

# Known issues

* Ideally we would have indexed individual outcomes _while_ they were made public or became available. _This, being an experiment conceived near the end of the grant, does not represent the ideal case_. 
* In our case the dates on the blog posts don't correspond to the dates the products went live.
* Very large files still don't play super nice with public git repositories.
* Summarizing results has to happen in two places, NSF reporting and the blog. Ideally posts here could be batch processed for the format that fastlane lets you batch load.
* Perhaps it could be the other way around, report.research.gov could generate the markdown of the reports section and users could post it to the web as desired.
* We need to more finely tune the meta tags for the site, and potentially individual posts.

# Contributing

* Here is the git repository for the site: [https://github.com/bioip/bioip.github.io](https://github.com/bioip/bioip.github.io). 
* Feel free to use the [issue tracker](https://github.com/bioip/bioip.github.io/issues) to comment or add questions about the project.

# Disclaimer 

This project was funded by NSF-ABI-1356381. Any opinions, findings and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation. 

