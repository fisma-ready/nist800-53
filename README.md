# NIST 800-53

This project maintains [NIST Special Publication 800-53](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf) and its controls in a structured form that is easy to annotate and repurpose.

### Background

The [National Institute of Standards and Technology](http://www.nist.gov/) (NIST) issues and maintains a special publication, 800-53, named **[Security and Privacy Controls for Federal Information Systems and Organizations](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf)**.

800-53 provides a catalog of security "controls" &mdash; standards, processes, and practices &mdash; that must be considered when designing and deploying an information system in the US federal government. Controls can also have "enhancements", which describe additional practices to be considered when implementing a control.

You can read more on the [background and history of 800-53](https://en.wikipedia.org/wiki/NIST_Special_Publication_800-53) on Wikipedia.

There are a total of 256 controls with 666 enhancements, spread across 18 categories ("families"). NIST provides a [consolidated XML feed](https://nvd.nist.gov/static/feeds/xml/sp80053/rev4/800-53-controls.xml) of all controls and enhancements.


### Technology neutral

NIST is clear that the controls are designed, as much as possible, to be agnostic to the selection of specific technologies ([PDF](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf), p10):

> The security controls in the catalog with few exceptions, have been designed to be policy- and technology-neutral. This means that security controls and control enhancements focus on the fundamental safeguards and countermeasures necessary to protect information during processing, while in storage, and during transmission. ... It should also be noted that while the security controls are largely policy- and technology-neutral, that does not imply that the controls are policy- and technology-unaware. Understanding policy and technology is necessary so that the controls are meaningful and relevant when implemented.

### Public domain

As NIST states, 800-53 is public domain in the United States ([PDF](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf), p3):

> This publication may be used by nongovernmental organizations on a voluntary basis and is not subject to copyright in the United States. Attribution would, however, be appreciated by NIST.