

# EASIER_CORPUS
Repository for easier corpus. Represented by:

| TASK | # |
| --- | --- |
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
We performed an agreement between the original annotator(1) and other two different annotators(2) (3).
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

Please, if you use our corpus, remember to cite this paper:
# REFERENCE:

Please, if you use our corpus, remember to cite this paper:

Alarcon R, Moreno L, Martínez P (2023) EASIER corpus: A lexical simplification resource for people with cognitive impairments. PLOS ONE 18(4): e0283622. https://doi.org/10.1371/journal.pone.0283622

# DIFUSSION RIGHTS:
This corpus is under CC BY-NC-ND 4.0, https://creativecommons.org/licenses/by-nc-nd/4.0/ license.

# Acknowledgments

- This work is part of the R\&D\&i ACCESS2MEET (PID2020-116527RB-I0) project financed by MCIN AEI/10.13039/501100011033/, and the "Intelligent and interactive home care system for the mitigation of the COVID-19 pandemic" project (PRTR-REACT UE) awarded by CAM. CONSEJERÍA DE EDUCACIÓN E INVESTIGACION.

