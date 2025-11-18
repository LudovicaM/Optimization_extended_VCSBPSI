# Master_Thesis
Master_thesis
The files [CODE] contain the copy of the python code used for generating the results.

1 - instances generation: stochastic instances generated to feed the model

2 - instances deterministic: deterministic instances obtained by averaging the values of the items, then used for the EVP.

3 - deterministic opt_model: used to find bins for the first-stage decision, with no uncertainty, using the deterministic instances. Hence, to compute the EVP. 

4 - Monte Carlo simulation: optimization model to generate results for the Monte Carlo simulation  of the EVP, where I used determinstic bins for first stage, and then introduce uncertainty through items' scenarios at second stage.

5 - Optimization_model_2SS: two- stage stochastic slolution model, which introduces uncertainty from the start, accounting for scenarios in the decision of the bins.

6 - heuristic SS BFD: heuristic algorithm which benchmarks the 2 stage stochastic solution approach

The Excel file **"FINAL_RESULTS"** contains all the results from the test carried out for the master thesis, reporting on the different sheets the outcomes of different parameters combination. In the summary sheets there are some tables that compares the results. 

The ZIP file **Instances** contains the instances used for the 2SS model, while the 3 single files called instance_spx_n38 contain, for each spread of items, the deterministic instances used for the EVP. 
