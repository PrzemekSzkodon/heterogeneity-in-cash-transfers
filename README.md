# D300 Project — Haushofer & Shapiro (2016)

## Data
Download UCT_FINAL_CLEAN.dta from Harvard Dataverse:
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/M2GAZN
Place in a folder called dataverse_files/ in the same directory as the notebook.

## Environment
conda env create -f environment.yml
conda activate causal_ml

## Running
Run all cells in order. Figures save to output/ automatically.

## Structure
1. Data preparation
2. Randomisation validation
3. Baseline balance
4. ANCOVA benchmark ATE
5. Post-selection ATE estimation
6. Honest causal forest
7. BLP, GATEs and CLAN
8. OLS of tau_hat on X (not included in D300 report)
9. Policy trees (not included in D300 report)