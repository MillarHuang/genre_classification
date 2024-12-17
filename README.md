# genre_classification
end to end machine learning pipeline demo

# Run on command
mlflow run . -P hydra_options="main.project_name=genre_classification_prod"

# Execute one or more steps of pipeline:download, preprocess,check_data,segregate,random_forest,evaluate
## Execute download and preprocess steps
mlflow run . -P hydra_options="main.execute_steps='download,preprocess'"
