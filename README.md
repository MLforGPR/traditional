# machine learning for GPR
This repository contains the code for the machine learning and data pipeline for the Capstone project.
The code is organized in the following way:
```
root directory
│   decision_tree (folder containing the decision tree model)
│   random_forest (folder containing the random forest model)
|   SVM (folder containing the SVM model)
|   CNN (folder containing the CNN model)
|   ...
│   data_pipeline.ipynb (data pipeline)
│   validation.ipynb (validation)
│   ...
```
To run the code, please pull this repository and `data_preprocessing` repository to the same directory. The `data_preprocessing` repository can be found [here](https://github.com/MLforGPR/data_preprocessing).

## Data Pipeline
This section describes the data pipeline for the Capstone project. The data pipeline is implemented in the Jupyter notebook `data_pipeline_*.ipynb`. The data pipeline is organized in the following way:
```
root directory
│   data_pipeline_1st2nddataset.ipynb (final data pipeline for SVM)
│   data_pipeline_1st2nddataset_cnn.ipynb (final data pipeline for CNN)
|   data_pipeline_combined.ipynb (data pipeline for 1st dataset only)
|   data_pipeline_layer.ipynb (data pipeline for detecting top layers)
|   ...
```

### Final Data Pipeline
The final data pipeline is implemented in the Jupyter notebook `data_pipeline_1st2nddataset.ipynb` and `data_pipeline_1st2nddataset_cnn.ipynb`. `data_pipeline_1st2nddataset.ipynb` is the data pipeline for SVM and `data_pipeline_1st2nddataset_cnn.ipynb` is the data pipeline for CNN.

### Previous Data Pipeline
`data_pipeline_combined.ipynb` and `data_pipeline_layer.ipynb` are the data pipeline for the 1st dataset only. They are not capable of handling the 2nd dataset and 3rd dataset.

## Validation
This section describes the validation for the Capstone project. The validation is implemented in the Jupyter notebook `validation.ipynb` and `validation_cnn.ipynb`. `validation.ipynb` is the validation for SVM and `validation_cnn.ipynb` is the validation for CNN. The validation is organized in the following way:
```
root directory
│   validation.ipynb (validation for SVM)
│   validation_cnn.ipynb (validation for CNN)
|   ...
```

This code also contains the code for recording the results of the validation. The results will be saved in the MP4 file `validation.mp4` and `validation_cnn.mp4`.