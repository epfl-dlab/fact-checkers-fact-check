# Code and data for "Can online attention signals help fact-checkers fact-check?"

This repository contains the data and code of the paper "Can online attention signals help fact-checkers fact-check?" ([which you can read clicking here](https://arxiv.org/abs/2109.09322)):
  
~~~bibtex
@inproceedings{ribeiro2022factcheck,
  title={Can online attention signals help fact-checkers fact-check?},
  author={Ribeiro, Manoel Horta and West, Robert},
  booktitle={Workshop Proceedings of the 16th International AAAI 
             Conference on Web and Social Media (MEDIATE)},
  year={2022}
~~~

## Relevant files

- `analysis.ipynb` reproduces Figures 3-8.

- `organizations.csv` — organization to country mapping.

- `df_ts.csv` — weekly attention (`max_ratio`) going to each country for each claim.

- `df_casv.csv` — weekly attention-derived metrics (e.g., CASV) going to each country for each claim. 

- `df_fc.csv` — relevant fact-checking efforts for the considered claims.

- `original_database.csv` — original database provided by IFCN.

- `claim-clusters/` — claim cluster extracted from original database.

- `kg_ids.json` — mapping between claim clusters and knowledge graph ids.
