# This code was used to develop and evaluate machine learning models for the prediction of 1-year major adverse limb event or death following endovascular intervention for peripheral artery disease using the Vascular Quality Initiative Database in the manuscript entitled "Using machine learning to predict outcomes following endovascular intervention for peripheral artery disease" by Li and colleagues. The code was written in R verison 4.3.1.

Purpose: The machine learning models are designed to predict 1-year outcomes following endovascular intervention for peripheral artery disease using pre-, intra-, and post-operative data available through the Vascular Quality Initiative Database.

Inputs: There are 112 potential input features (75 pre-operative [demographic/clinical], 24 intra-operative [procedural], and 13 post-operative [in-hospital course/complications]) from the index hospitalization.

Outputs: Binary prediction positive or negative for 1-year major adverse limb event (composite of thrombectomy/thrombolysis, surgical reintervention, or major amputation) or death.

Constraints: The models were developed using data from the Vascular Quality Initiative Database, a volunary registry primarily comprising data from North American centers. Future work is needed to assess generalizability of the models in a prospective setting.
