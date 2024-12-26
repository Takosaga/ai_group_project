## Data Download ##
gcs_file_download.ipynb has to be run first to download all data from Dimitrijs' public GCS - testset which includes images and labels, unlabeled test sets seperated into 5 sets. skip this step if you do not plan to replicate the testing and evaluation on your local machine. to just see results view the other four jupyter notebooks.

## Test Evaluation ##
initial_model_evaluation.ipynb tests the base model with varying values for IoU and conf and saves all the results (IoU, conf, p, r, mAP50, mAP50-95) for each class in seperate csv files which can be used later for further evaluation.

augmented_model_evaluation.ipynb tests the augmented model with varying values for IoU and conf and saves all the results (IoU, conf, p, r, mAP50, mAP50-95) for each class in seperate csv files which can be used later for further evaluation.

The initial testing in both files conduct an initial test on the respective models using default conf and IoU values and saves predictions.json and the associated plots. This can be used to obtain a general evaluation of the model.

## Unlabeled Evaluation ##
