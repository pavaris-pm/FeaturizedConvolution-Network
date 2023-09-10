# Enhancing Features Quality through Transformation with the `FeaturizedConvolution` Network 🔥🏆
---


***Remarks:*** As of a survey with some classmates until September 10th, This is the `smallest` and `fastest` neural network model in the Deep Learning class right now! 🥇


---


<img align="middle" width="900" src="https://github.com/pavaris-pm/FeaturizedConvolution-Network/blob/main/featurizedconv.jpg">


1.   smaller than `AutoML` ensemble model params that stacked many models in many layers (e.g. WeightEnsembleL2/L3 from AutoGluon)

2.   obtain `81.25% accuracy`✅ by containing only `176 parameters`! which is smaller than the professor model (neural network with 209params achieving 76% accuracy)
<img align="middle" width="500" src="https://github.com/pavaris-pm/FeaturizedConvolution-Network/blob/main/custommodel_size_new.PNG">

4. faster training time `(<30 seconds with batch size set to 10)` even it utilize CPU as an accelerator ⚡

5. no need for ensembling of many trees that required many increased parameters 🌳

6. achieves `competitive performance` with gradient-boosting algorithm (e.g. catboost@acc79, [best-200iterations]catboost@acc82) and reveals an interesting performance compared to another deep learning model according to its smaller model size (e.g. professorModel@acc76) ⛹

---
- Credits: This Architecture was designed by `Mr. Pavaris Ruangchutiphophan` inspired by an idea of 1-dimensional convolution on signal data
---
