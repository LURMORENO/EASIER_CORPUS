# EASIER_CORPUS
Repository for easier corpus. Represented by:

| Complex Words detected | 8155 |
| Suggested synonyms | 7892 |



Each line represents a sentence with one complex word annotation and relevant information, each separated by a TAB character.

## FOR THE CWI DATASET:
  * The first column shows the ID of the document.
  * The second column shows the ID of the sentence for a certain word.
  * The third column shows the sentence.
  * The fourth and fifth column shows the offset of the target word.
  * The sixth shows the target word.
  * The seventh column shows the gold-standard label for the binary task.
  
## FOR THE SG/SS DATASET:
  * The first column shows the ID of the document.
  * The second column shows the ID of the target word.
  * The third column shows the target word.
  * The fourth column shows the sentence.
  * The fifth column shows the suggested synonyms for the target word separated by a comma.
  

## AGREEMENT
We performed an agreement between the original annotator(1) and other two different annotators(1) (2).
### COHEN´S KAPPA
| Annotators | Score |
| --- | --- |
| (1) (2) | 0.6094 |
| (1) (3) | 0.6422 |
| (2) (3) | 0.6739 |

### FLEISS KAPPA
| Annotators | Score |
| --- | --- |
| (1) (2) (3) | 0.641 |

