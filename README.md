# deep Classifier project

## workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config.
6. Update the components
7. Update the pipeline
8. Test run pipeline stage
9. run tox for testing your package
10. Update the dvc.yaml
11. run "dvc repro" for running all the stages in pipeline

![img](https://raw.githubusercontent.com/c17hawke/FSDS_NOV_deepCNNClassifier/main/docs/images/Data%20Ingestion%402x%20(1).png)

MLFLOW_TRACKING_URI=https://dagshub.com/rajashekarnagalikar/DeepCNNClassifier.mlflow \
MLFLOW_TRACKING_USERNAME=rajashekarnagalikar \
MLFLOW_TRACKING_PASSWORD=005a680f43f56cef91d36a169a6b1e2634290225 \
python script.py