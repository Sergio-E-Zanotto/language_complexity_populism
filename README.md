# Language Complexity in Populist Rhetoric

This repository contains the code and data for the paper **Language complexity in populist rhetoric**:

- To appear in: Sergio E. Zanotto, Diego Frassinelli and Miriam Butt. 2024. Language complexity in populist rhetoric, in *Proceedings of the 4th Workshop on Computational Linguistics for the Political and Social Sciences*

## Description

This repository includes scripts, data, and analysis results used in the study of language complexity within populist rhetoric. The project explores and profiles linguistic features in political texts, focusing on how language complexity varies in populist discourse.

## Structure


### Data

- `Data/AoA_data.csv`: Data for age of acquisition of Italian words.
- `Data/concreteness_it.csv`: Data for concreteness ratings in Italian.
- `Data/it_50k.txt`: A text file containing a list of the 50,000 most frequent Italian words.
- `Data/maggioranzainparlamento.csv`: Data related to parliamentary majority.
- `Data/offical_text_profiling_impaqts.csv`: Final data with the feature profiling of the texts from subcorpus C (1990s onward) of the IMPAQTS corpus.
- `Data/populism-anticentrism.csv`: Dictionary of seed words on populism and anti-elitism.
- `Data/UD_politicians.csv`: Features calculated with the UD profiling tool.

### Scripts

- `Scripts/Data_Preparation_Features_calculation.ipynb`: Jupyter notebook for data preparation and feature calculation.
- `Scripts/Lasso_inpaqts.Rmd`: R Markdown file showing feature selection and regression results.

