# Temporal Information and Event Markup Language - TIE-ML

License: Apache License Version 2.0

(C) 2021 by Ali Aljubailan, [Damir Cavar], [Billy Dickson], Soyoung Kim

Brought to you by the [NLP-Lab] at [Indiana University at Bloomington](https://www.indiana.edu/).


## Introduction

TIE-ML is a markup strategy and annotation schema to improve the productivity and accuracy of temporal and event related annotation of corpora to facilitate machine learning based model training. For the annotation of events, and temporal sequencing and duration of events, it is significantly simpler, and thus easier to use than much more sophisticated formalisms and approaches such as [TimeML]. Annotations of corpora using [TimeML] can be mapped to TIE-ML with a loss, and TIE-ML annotations can be fully mapped to [TimeML] with certain under-specification.

The TIE-ML XML annotation standard proposal comes with an XML Schema (using the 1.1 recommendation). To use the XML Schema in your own TIE-ML XML annotation files, include it in the following way:

```xml
  <?xml version="1.0" encoding="UTF-8"?>
  <tieml xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:noNamespaceSchemaLocation="https://nlp-lab.org/tieml.xsd">
    ...
  </tieml>
```

## Sample Corpus

The *data* folder contains samples for different languages using ISO language codes as folder names. Please consult the *README.md* files in each of the folders for more details about the samples and annotations.

Note that we are working on a temporal and event annotation of the 10% [Penn Treebank] corpus that is distributed with the [NLTK] data set.


## Scripts and Tools


## Documentation


## Publications

- D. Cavar, B. Dickson, A. Aljubailan, S. Kim (2021) *[Temporal Information and Event Markup Language: TIE-ML Markup Process and Schema Version 1.0](https://arxiv.org/abs/2109.13892)*, In Proceedings of [SEMAPRO 2021](https://www.iaria.org/conferences2021/SEMAPRO21.html), Barcelona, Spain.



[Damir Cavar]: https://www.linkedin.com/in/damircavar/ "Damir Cavar"
[Billy Dickson]: https://www.linkedin.com/in/billy-dickson/ "Billy Dickson"
[NLP-Lab]: https://nlp-lab.org/ "NLP-Lab"
[NLTK]: https://nltk.org/ "Natural Language Toolkit"
[CoNLL-U]: https://universaldependencies.org/format.html "CoNLL-U"
[Penn Treebank]: https://catalog.ldc.upenn.edu/LDC99T42 "Penn Treebank"
[TimeML]: https://en.wikipedia.org/wiki/TimeML "TimeML"
