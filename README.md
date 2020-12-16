# Udacity_Kaggle_Riid
My final project for ML engineer nanodegree

Packages to used on model file include:

Lightgbm\
Datatable\
Optuna\
Pickle\
Pandas\
Numpy\
Gc\
sklearn.metrics\
Collections\
Tqdm.notebook

Also, I used a google cloud AI instance with 16 VPU and 128 MB with 200 MB disk space. I saved final model in a pickle file on this instance. Read in data to contain the necessary features saved in datatable .jay format for download/upload in Kaggle notebook for inference.

The train.jay and valid.jay are a result of the above process. 
To run the am_lgbm_project_r1 notebook, you will need to download the main train.csv from the Kaggle Riid Competition data page here: https://www.kaggle.com/c/riiid-test-answer-prediction/data

Lastly, to run lgbm_inference_kaggle.ipynb, you will need the same packages as modeling file (shown above). 
Also, the data needed for inference will be in the Kaggle folder. 
You will need to upload these data files into a Kaggle notebook on their cloud notebook.
