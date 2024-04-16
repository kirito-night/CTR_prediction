# CTR prediction


The project trains models on a training dataset with click-through rate (CTR) values to predict the CTR for each row in the test dataset. Preprocessing of tabular data involves handling missing values, processing time variables, standardizing numerical features, and encoding categorical features. Initially, a Multilayer Perceptron (MLP) is used as a baseline for testing. Subsequently, a Deep Cross Network (DCN) is employed for prediction. DCN effectively learns feature interactions by utilizing deep learning and cross-layer structures, enabling it to capture and understand the complex non-linear relationships in advertising data, thus improving prediction accuracy.

Through multiple rounds of cross-validation experiments, it was found that DCN significantly outperforms MLP, demonstrating higher accuracy and stability. The predicted results are also more reasonable. 
