# Repository Structure

## Data
Contains preprocessed data files.

- **`sample_data.csv`**: Sampled balanced dataset from the original dataset.  
- **`industrial_data.txt`**: 62 industrial data samples from Amazon.  
- **`train_processed.csv`**: Train dataset from the `sample_data.csv` after preprocessing.  
- **`dev_processed.csv`**: Dev dataset from the `sample_data.csv` after preprocessing.  
- **`test_processed.csv`**: Test dataset from the `sample_data.csv` after preprocessing.  
- **`industrial_data_processed.csv`**: `industrial_data.txt` after preprocessing.  

## Images
Contains all the output images from notebooks.

## Notebooks
- **`training_models.ipynb`**:  
  Trains models and tests performance on the domain A dataset (source dataset).  

- **`evaluation.ipynb`**:  
  Performs XAI evaluation using the trained models on the domain B dataset (target dataset).
