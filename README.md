# drug-pair_cell-synergy

Drug combination therapy has emerged as a highly promising approach in cancer treatment. Nevertheless, the sheer magnitude of potential drug combinations poses a significant challenge for screening synergistic combinations through laboratory experiments alone. Consequently, computational screening has become a crucial method for prioritizing drug combinations.

In this context, we employ cell and gene expression data, subjecting them to a Multilayer Perceptron (MLP). Simultaneously, drug pair data is processed through XGBoost. The resultant features learned from both models are combined and input into a fully connected layer, serving as a binary classifier to predict whether drug-drug combinations are antagonistic or synergistic.

**Required libraries**
pandas
numpy 
rdkit
xgboost 
sklearn
tensorflow 

**Python ver.3.12**

*For questions/suggestions or technical errors, write to us at aamirmehmood@sjtu.edu.cn.*
