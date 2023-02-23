# deep_cnn_model
## workflow

```
1.update config.yaml
```
```
2.update secret.yaml
```
```
3.update params.yaml
```
```
4.update the entity
```
```
5.update configuration mannager in src config
```
```
6.update the components
```
```
7.update the pipeline
```
```
8.test run pipeline stage
```
```
9.update the dvc.yaml
```
```
10.run tox for testing your package
```
```
11.run "dvc repro" for running all the stages in pipeline
```

MLFLOW_TRACKING_URI=https://dagshub.com/akhilpratap620/deep_cnn_model.mlflow \
MLFLOW_TRACKING_USERNAME=akhilpratap620 \
MLFLOW_TRACKING_PASSWORD=32a86114cbf605d19e49f76367dd9a4a791589e9  \
python script.py
