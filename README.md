# Ontology repository (LEDS project, ASP-F group)

This repository is part of the work of the [ASP-F](http://www.leds-projekt.de/de/arbeitspakete.html#asp-f---vernetzte-e-government-dienste) group from the [LEDS project](http://www.leds-projekt.de/) (in German). We want to plan, discuss and develop our ontologies/vocabularies publicly, therefore a repository on Github.

### No distinction between the terms "vocabulary" and "ontology"

We use ontology and vocabulary as synonyms and no distinction is made between. The reason is, that there is no clear distinction between them. Both possess things which are part of the counterpart too. W3C says:

> There is no clear division between what is referred to as “vocabularies” and “ontologies”. The trend is to use the word “ontology” for more complex, and possibly quite formal collection of terms, whereas “vocabulary” is used when such strict formalism is not necessarily used or only in a very loose sense. Vocabularies are the basic building blocks for inference techniques on the Semantic Web. *(Source: https://www.w3.org/standards/semanticweb/ontology)*

There is also an interesting discussion on [stackoverflow](http://stackoverflow.com/questions/20200270/ontology-vs-vocabulary).

## Requirements for ontologies

Our use case is located in **Open Data** and **Open Government** and characterized by the following parameter:
* Broad spectrum of people using and participating
* Education/qualification of the people differs: technicans, domain experts, ontologists, end-users. Groups are not distinct and may overlap.
* Broad spectrum of domains, which need to be integrated. We want to create an ontological foundation for basic / mainstream use cases, which means, that each ontology is more like a set of modules which can be used differently in different use cases.

Therefore we have the following requirements for the ontologies we create or use:
* **Easy to understand** - We know, its a buzz-phrase. An ontology should provide a documentation, containing an explanation about the essence/main idea of the ontology. Classes and properties of the ontology should named according to the main idea. Avoid not common abstract concepts or terms or describe them clearly.
* **Easy to use** - Buzz-phrase too, what we mean is that the documentation of the ontology comes examples in RDF, how to use its (major) classes and properties, clearly written, maybe complemented by use cases.
* **Open for integration** - An ontology contains properties, which are not too restrict with domain and range. Fixed domain and range should be added by the end-user, who adjust an ontological basis for his application.

## Ontologies

We are working on the following ontologies. Each one is considered a so called domain ontology and describes a certain area of interest. Further ontology types are core ontologies (or vocabularies) such as Dublin Core and task ontologies, which contain additional facts and rules, to modify a certain domain on behalf of an application.

### Building ontology

This ontology describes buildings, usually structures which contain at least two rooms and a roof. We wanted to keep it simple, but the main focus lies on architectural facts.

[Go to overview](https://github.com/AKSW/leds-asp-f-ontologies/tree/master/ontologies/building)

### Elevator ontology

This ontology describes elevators inside or outside a building.

[Go to overview](https://github.com/AKSW/leds-asp-f-ontologies/tree/master/ontologies/elevator)

### FAMOS ontology

This ontology describes buildings based on the [FAMOS](http://www.kesslersolutions.de/cafm-loesung/cafm-software-famos.html) software. It references the building ontology to allow later interconnections.

[Go to overview](https://github.com/AKSW/leds-asp-f-ontologies/tree/master/ontologies/famos)

## Conventions

* URIs in ontologies: camel case, first letter is up
* class names: camel case, first letter is up
* properties: camel case
  * no distinction between object and datatype properties concerning the names

## License

We didn't decide the license yet, so if you consider using these ontologies, ask us and we find a solution.

Contact details:
* [FKoestner](https://github.com/fkoestner)
* [Konrad Abicht](http://aksw.org/KonradAbicht.html)
