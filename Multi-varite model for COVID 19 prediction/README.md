# Muti-varite model for COVID 19 Prediction

This is the a data science project mainly focus on the prediction for the development of COVID in Virginia State. The folder contians 4 parts: 1 written report, 1 presentation slide, 2 model folder. The data used in this research is presented in the model folder.

# Usage

The datasets can be found by the following links:
1. the over all situation of Virginia (cases and death): https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36
2. hospitalization: https://data.virginia.gov/Government/VDH-COVID-19-PublicUseDataset-KeyMeasures-Hospital/28wk-762y
3. intervention: https://github.com/OxCGRT/covid-policy-tracker
4. recovered cases: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports_us

The file SIR_improved_with_sliding_window.ipynb is the code for implementing SIR model and the file XGB.ipynb is the code for XGBoost
The datasets are imported by mounting the Google Drive.

# Abstract

The research is devoted to predicting the volume of existing COVID-19 cases in the future to illustrate the situation of the pandemic to facilitate policymaking. In this research, my team member and I proposed multi-variate method takes those factors into consideration based on an eXtreme Gradient Boosting (XGBoost) model with K-fold training. Unlike traditional compartmental models in epidemiology, the sequence of time is ignored during training with shattered data. The proposed model is tested on a Virginia state dataset with a comparison of SIR model. It turns out that the XGBoost model has an outstanding performance in prediction accuracy and much better generalization than the SIR, especially for a long-term prediction.
