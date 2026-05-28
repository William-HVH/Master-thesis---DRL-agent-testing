# Master-thesis---DRL-agent-testing
This codebase presents a FinRL inspired setup, that trades on 11 sector ETF's + cash
It then presents 3 experiments:
1) A2C and PPO agents are trained and compared with classical portfolio baselines, including equal weighting, buy-and-hold and mean-variance optimization
2) Selected policies are tested with SHAP to extract feature importance and test policy/SHAP robustness
3) A decision tree regressor is trained on the policies, included max depth and regularized version, to shed light on the performance and fidelity to the teacher

For more meaningful interpretation, I recommend collapsing the helper function cells in the jupyter notebook, as the codebase is long

*Note, installation of libaries are not thoroughly checked if one wants to rerun the entire codebase. Additional installs may be needed although I've tried to cover what's necessary. This is due to running it in a separate kernel with different library. For an exhaustive list, check the csv - although many of those are downloaded automatically from the finrl library, and some may not be used.
