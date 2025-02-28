![Transportome](https://github.com/RekerLab/Transportome/assets/127516906/1111fe5d-7594-4296-af9e-a3479a4ce59d)

For more information, please refer to the [associated publication](https://www.nature.com/articles/s41551-023-01128-9)

If you use this data or code, please kindly cite: Shi, Y., Reker, D., Byrne, J.D. et al. Screening oral drugs for their interactions with the intestinal transportome via porcine tissue explants and machine learning. Nat. Biomed. Eng (2024). https://doi.org/10.1038/s41551-023-01128-9 

The following files are currently stored in this repository
| Filename  | Content |
| ------------- | ------------- |
| code.py | Python code to run retrospective evaluations, model fitting, and predictions  |
| database.tsv  | The main database used for initial model fitting  |
| database_drugbank5_only.tsv  | Only the DrugBank fraction of the main database  |
| additional_X.tsv  | Additional (non-)substrates extracted from active learning literature search   |
| investigational_compounds.tsv  | Investigational drugs currently undergoing (pre) clinical evaluation   |
| investigational_library.tsv  | Investigational drugs that were experimentally characterized by us  |
| drugbank5_approved.smiles  | DrugBank 5 approved small molecules  |

## Requirements
The code was implemented using
- [Python 3.7.9](https://www.python.org/)
- [RDKit 2020.09.1](https://www.rdkit.org/docs/Install.html)
- [Scikit-learn 1.0.2](https://scikit-learn.org/stable/)
- [Imblearn 0.9.0](https://imbalanced-learn.org/stable/)
- [DeepChem 2.7.1](https://deepchem.io/)
- [DEEP GRAPH LIBRARY 2.0.0](https://www.dgl.ai/)
- [DGL-LifeSci 0.3.1](https://lifesci.dgl.ai/index.html)
