# AnalogyKB

Resources for our paper: Unlocking Analogical Reasoning of Language Models with A Million-scale Knowledge Base

## Dataset Format

Each data entry in the dataset is a JSON object containing the following fields:

- `relation`: the relations in each analogy
- `tuple`: two tuples (term pairs) under analogous relations can be analogous

## Ethics Statement
### Use of Human Annotations
The annotations of relation pairs in AnalogyKB are implemented by annotators recruited by our institution.
The construction team remains anonymous to the authors, and the annotation quality is ensured by using a double-check strategy.
We ensure that the privacy rights of all annotators are respected throughout the annotation process. All annotators are compensated above the local minimum wage and consent to the use of AnalogyKB for research purposes, as described in our paper.


### Risks
The database is sourced from publicly available sources, Wikidata and ConceptNet. 
However, we cannot guarantee that it is free of socially harmful or toxic language. 
Additionally, analogy evaluation relies on commonsense, and different individuals with diverse backgrounds may have varying perspectives.


