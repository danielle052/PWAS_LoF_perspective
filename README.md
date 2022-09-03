# PWAS_LoF_perspective
This repository contains:
1) update_firm_score.py- updates FIRM scores by different hypotheses. 
2) parse_open_target_data.py- script for retrieving and parsing open targets data.
3) compare_new_pwas_results_to_GT.py- compares the new PWAS results (after the scores have been updated) with the ground truth.
4) README

Running PWAS with new hypotheses for scoring LoF mutations:
1) Clone this repository.
2) Follow steps 1-2 in the README in this repository: https://github.com/nadavbra/pwas
3) Choose hypothesis from update_firm_score.py (or add a new hypothesis with the same contruct to this file) and run the relevant function.
4) Follow steps 3-4 in the README in this repository: https://github.com/nadavbra/pwas
5) To compare the results to the Open Targets data run plot_new_discovered_genes() from compare_new_pwas_results_to_GT.py
