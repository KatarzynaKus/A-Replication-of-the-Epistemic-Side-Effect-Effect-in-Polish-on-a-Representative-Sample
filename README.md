# A Replication of the Epistemic Side-Effect Effect in Polish on a Representative Sample

This study investigates whether the Epistemic Side-Effect Effect (ESEE) – a robust finding in experimental epistemology – can be replicated in Polish using a representative, non-convenience sample. The ESEE refers to the tendency of individuals to ascribe knowledge more readily when a foreseen side effect of an agent's action violates a norm, compared to when it promotes one (Beebe & Buckwalter, 2010). While ESEE has been replicated in several languages, earlier pilot studies in Polish produced mixed results, possibly due to differences in question phrasing or sampling biases.

To test the robustness of the effect in Polish, we designed a 3 (formulation of the knowledge claim: agentive, causal, or state-change) × 2 (type of side effect: harm vs help) × 2 (response format: forced-choice vs Likert scale) between-subjects experiment. Participants (N = 1310) were recruited by a professional panel (Ariadna) to ensure demographic representativeness. The study included several dependent measures probing knowledge attribution, belief, intentionality, and intention, with additional justifications collected for respondents’ answers. 

Results confirmed the presence of the ESEE in Polish across all knowledge formulations and both response formats. Meta-analytic estimation revealed a large effect size (SMD = 1.28, 95% CI: 0.95–1.60), consistent with or exceeding estimates from prior English-language studies. The study also replicated the Knobe effect for four Polish intentionality predicates and revealed subtle interactions between verb choice and strength of doxastic attribution. These findings contribute to the cross-linguistic generalizability of ESEE and provide new insights into the conceptual structure of knowledge and belief in Polish.

OSF PAGE: [https://osf.io/6xn27/](https://osf.io/6tvnh/). 

## Citation

If you used the this dataset, please cite it as:

> Zaręba, M., Kuś, K., Maćkiewicz, B., & Paprzycka-Hausman, K. (2025). A Replication of the Epistemic Side-Effect Effect in Polish on a Representative Sample. https://doi.org/10.17605/OSF.IO/6TVNH


## Structure of the repository

- `data` 
	- `Zbiór_UW_Marta_Zaręba_Esee_v4.sav` - raw data in SPSS `sav` format
	- `esee_in_polish_cleaned.csv` - CSV file with cleaned data
- `questionnaire`
  - `Questionnaire - ESEE in Polish` - a PDF file containing a description of the content for all 12 questionnaire groups.
- `codebook` 
	- `codebook.Rmd` - script for generating human and computer readable codebook for the dataset
	- `codebook.html` - a codebook
- `analysis` 
  - `analysis.Rmd` - script for cleaning data (produces `esee_in_polish_cleaned.csv` from raw dataset) and simple analyses; a short description of variables can be also found there
  - `analysis.html` - compiled report

