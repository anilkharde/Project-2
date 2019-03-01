# Project-2
Consumer Complaints Resolution

Consumer complaint resolution is important to any business. In this particular case we have been given details consumer complaints along with whether consumer disputed with the conclusion. If we are able to predict this , consumer likely disputed can be given more attention as to how the complaints are handelled as well as how to convincingly convey the final conlusions to them.

1. In data preparation step new features were added(Time difference between complaint received and addressed for the first time), irrelevant columns were dropped(zip code, postal code, etc), dummies were created for the categorical columns. Categories with only high frequencies were considered to avoid overfitting and to generalise the model.
2. Logistic regression, Random forest, Neural network, XGBoost machine learning algorithms were implimented. On top of all stacking logistic model was implimented taking into consideration the response of all other algorithms mentioned above.
3. Important features were identified.
4. Higest ROC AUC score obtained was 62%.
