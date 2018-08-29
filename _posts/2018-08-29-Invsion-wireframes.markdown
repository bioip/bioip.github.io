---
layout: post
title:  "Interfaces against an API"
date:   2018-08-28 14:37:06 -0500
categories: [software, howto, JSON]
---

One way to "rapidly" prototype new interfaces is to contract out to services.  Using TaxonWorks we proofed this concept with the design and implementation of a "matrix row coder", basically the functionality required to code a matrix of evolutionary or observation characters. Our internal team built out the API, sharing it with our contractors via a Docker container.  We worked one-to-one, tweaking the API.  The result was a applicatation whose javascript could stand-alone, i.e. it had not dependencies on the larger TaxonWorks interfaces, but could also be integrated into the TaxonWorks framework.

The git code-base.



