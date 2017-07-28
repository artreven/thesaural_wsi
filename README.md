# Thesaural Word Sense Induction
Data for discrimination of word senses using hypernyms.

The repository contains two datasets: cocktails and mesh.

#### Thesaurus
The thesaurus "All about cocktails" can be found in `cocktail.ttl` file in [turtle](https://www.w3.org/TeamSubmission/turtle) format.

The MeSH thesaurus is not contained in this repository. It can be found online at https://id.nlm.nih.gov/mesh/.

#### Corpora
The corpora are extracted using [Wikilinks](http://www.iesl.cs.umass.edu/data/wiki-links). Every folder contains a corpus related to an ambiguous cocktail name. In evert folder there exists a file `forms.tsv` containing all the surface forms of the cocktail name. The individual texts are stored in separate file. The naming convention for the file is the following:
> {numeric id}__{category name}.txt

The category name is the English [Wikipedia](https://en.wikipedia.org/wiki/Main_Page) id of the category, i.e. in order to go to the Wikipedia page of the category go to the URL `https://en.wikipedia.org/wiki/{category name}`.