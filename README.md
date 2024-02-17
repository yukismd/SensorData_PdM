# SensorData_PdM
## センサーデータを題材にした予知保全/Predictive Maintenanceユースケース

### Original Dataset
CMAPSS Jet Engine Simulated Data: https://data.nasa.gov/Aerospace/CMAPSS-Jet-Engine-Simulated-Data/ff5v-kuh6/about_data

### Code
- [code/0_dataPrep.ipynb](code/0_dataPrep.ipynb) - Original Datasetの処理
- [code/1_targetVariableAnalysis.ipynb](code/1_targetVariableAnalysis.ipynb) - ターゲット変数の分析
- [code/2_explanatoryVariableAnalysis.ipynb](code/2_explanatoryVariableAnalysis.ipynb) - ターゲット変数の分析
- [code/3_createModelingDataset.ipynb](code/3_createModelingDataset.ipynb) - モデリングデータ形式への変換
- [code/4_modelingDataset_split_trainTest.ipynb](code/4_modelingDataset_split_trainTest.ipynb) - モデリングデータのサンプリングとTrain/Test分割
- [code/5_predictionResultAnalysis.ipynb](code/5_predictionResultAnalysis.ipynb) - 予測結果の分析

### Driverless AI Experiment
Experiment Auto Doc: https://github.com/yukismd/SensorData_PdM/tree/main/DAI_Experiment
