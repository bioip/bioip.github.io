---
layout: post
title:  "Matrix row coder"
date:   2018-08-28 14:37:06 -0500
categories: [interfaces, software, APIs, howto]
---

Part of (rapidly) prototyping new software that will integrate with a larger platform means being able to use contractors or external parties to build out the interfaces. This project was an exploration of our ability to do that in TaxonWorks. We used a containerized version of TaxonWorks loaded with sandbox data as an API endpoint for our contractor.  While we worked on the API they worked on the interfaces. The result was a applicatation whose javascript could stand-alone, i.e. it had no dependencies on the larger TaxonWorks interfaces, but it could also be integrated into the TaxonWorks framework.

The interface was ultimately integrated into TaxonWorks and polished to a production level of readiness.

[Project link](https://github.com/SpeciesFileGroup/matrix_row_coder).



