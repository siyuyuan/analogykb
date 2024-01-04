# AnalogyKB

Resources for our paper: ANALOGYKB: Unlocking Analogical Reasoning of Language Models with A Million-scale Knowledge Base

## Dataset Format

- `Same_Relation_Wikidata/ConceptNet.json`: Within each relation, analogies of the same relation can be naturally formed, *Up is to Down as High is to Low*.
- `Analogous_Relation_Wikidata/ConceptNet.json`: the term pairs between two relations can also form analogies, as long as they have analogous structures.
For example, *Tim Cook is to Apple as Joe Biden is to USA*, where CEO (Relation 1) is analogous to head of state (Relation 2).

Each data entry in AnalogyKB is a JSON object containing the following fields:

- `relation`: the relations in each analogy
- `tuple`: two tuples (term pairs) under analogous relations can be analogous

## Data Statistics
| Source     | \# Term Pair | \# Rel(s) | Analogy Acc. |
|------------|--------------|-----------|--------------|
| Analogies of the Same Relation | | | |
| ConceptNet | 75,019 | 27 | 98.50\% |
| Wikidata | 563,024 | 813 | 98.00\% |
| Analogies of Analogous Relations | | | |
| ConceptNet | 11,829 | 5 | 95.50\% |
| Wikidata | 382,168 | 98 | 96.00\% |
| Total | 1,032,040 | 943 | 97.00\% |

## Ethics Statement
### Use of Human Annotations
The annotations of relation pairs in AnalogyKB are implemented by annotators recruited by our institution.
The construction team remains anonymous to the authors, and the annotation quality is ensured by using a double-check strategy.
We ensure that the privacy rights of all annotators are respected throughout the annotation process. All annotators are compensated above the local minimum wage and consent to the use of AnalogyKB for research purposes, as described in our paper.


### Risks
The database is sourced from publicly available sources, Wikidata and ConceptNet. 
However, we cannot guarantee that it is free of socially harmful or toxic language. 
Additionally, analogy evaluation relies on commonsense, and different individuals with diverse backgrounds may have varying perspectives.


