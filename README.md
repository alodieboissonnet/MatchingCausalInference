# MatchingCausalInference
Matching methods for Causal Inference to assess a medical treatment effect in R

The goal of our project is to study the causal effect of tranexamic acid using on headtraumatized patients, using a dataset provided by the AP-HP, gathering medical information on victims of major trauma. In observational studies such as ours, one of the major difficulties is to deal with the absence of a proper control group. Indeed, contrary to randomized experiment, there is a bias in the administration of the treatment.


To cope with this issue, we focused on the use of matching methods. In (1), we introduce the associated statistical framework. In (2), we describe three of the main techniques used in matching: coarsened exact matching, cardinality matching and propensity matching. As little statistical evidence of these techniques’ efficiency is known, we designed and implemented experiments to provide empirical results. We generated several synthetic datasets with various underlying complexity and compared our methods on these datasets. In (3), we expose the methodology and results of this experiment. Eventually we applied our methods on the traumabase after pre-processing it. This gave us an estimation of the treatment effect, that we present in (4). Finally, as the use of traumabase implied missing data imputation, we studied the robustness to missing data of our three matching methods in (5).


See our report for details about our work and our results.
