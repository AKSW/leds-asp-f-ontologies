# Building ontology

This ontology describes fact about a building. In following figure illustrates this ontology. It depends on known vocabularies/ontologies like dc, dcterms, skos, geo, [wa](http://semweb.mmlab.be/ns/wa#) and schema.org. Upon the building ontology, more detailed ontologies can be built, like the building [accessibility ontology](https://github.com/AKSW/leds-asp-f-ontologies/tree/master/ontologies/building-accessibility). 

Furthermore the building ontology helps formulate constraints ([SHACL rules](https://www.w3.org/TR/shacl/)). There are SHACL rules available, which describe accessibility aspects of a building, for instance, if [entrance is partyl/fully accessible by wheelchair users](https://github.com/k00ni/shacly/tree/master/constraint-groups/build_Building).

![](illustration.png)

## Acknowledgements

The building ontology is partly inspired and based on ideas of M. Goetz and A. Zipf (Related paper: [Extending OpenStreetMap to Indoor Environment: Bringing Volunteered Geographic Information to the Next Level](http://koenigstuhl.geog.uni-heidelberg.de/publications/2011/Goetz/Goetz-Zipf_2011_IndoorOSM.pdf)). We kept the focus on architectural information and included elements from the following vocabularies:

* [Dublin Core](http://purl.org/dc/elements/1.1/)
* [The vocabulary for (L)OD description of wheelchair accessibility](http://semweb.mmlab.be/ns/wa#)
* [SKOS](http://www.w3.org/2004/02/skos/core#)
