# SensorData_PdM
## センサーデータを題材にした予知保全/Predictive Maintenanceユースケース

***

Slide: [Data analysis guideline for manufacturing v240309.pdf](./Data%20analysis%20guideline%20for%20manufacturing%20v240309.pdf)

***

### Original Dataset
CMAPSS Jet Engine Simulated Data: https://data.nasa.gov/Aerospace/CMAPSS-Jet-Engine-Simulated-Data/ff5v-kuh6/about_data  
"train_FD002.txt"を利用

### Code(Notebook)
- [code/0_dataPrep.ipynb](code/0_dataPrep.ipynb) - Original Datasetの処理
- [code/1_targetVariableAnalysis.ipynb](code/1_targetVariableAnalysis.ipynb) - ターゲット変数の分析
- [code/2_explanatoryVariableAnalysis.ipynb](code/2_explanatoryVariableAnalysis.ipynb) - ターゲット変数の分析
- [code/3_createModelingDataset.ipynb](code/3_createModelingDataset.ipynb) - モデリングデータ形式への変換
- [code/4_modelingDataset_split_trainTest.ipynb](code/4_modelingDataset_split_trainTest.ipynb) - モデリングデータのサンプリングとTrain/Test分割
- [code/5_predictionResultAnalysis.ipynb](code/5_predictionResultAnalysis.ipynb) - 予測結果の分析

### Driverless AI Experiment
 - Experiment Auto Doc: [DAI_Experiment](./DAI_Experiment)   
 - Driverless AI Experiment file (1.2GB): https://jp-public.s3.ap-southeast-1.amazonaws.com/other/PdM/h2oai_experiment_83b7cd5c-bcb1-11ee-a7bd-2e53304ac579.dai
