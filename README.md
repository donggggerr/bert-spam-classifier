# SPAM Detection Using BERT

## Setup Instructions (Google Drive)

1. Go to [https://www.kaggle.com/datasets/imdeepmind/preprocessed-trec-2007-public-corpus-dataset](https://www.kaggle.com/datasets/imdeepmind/preprocessed-trec-2007-public-corpus-dataset)
2. Download the dataset **processed_data.csv**
3. Unzip the file
4. Go to [https://drive.google.com](https://drive.google.com)
5. Click the **+ New** button → select **New Folder**
6. Name the folder **BERT_Dataset**, then click **Create**
7. Open the **BERT_Dataset** folder
8. Click **+ New** → select **File Upload**, then choose the unzipped dataset file:  
   **processed_data.csv**
9. Confirm the dataset has uploaded to this path:  
   `/MyDrive/BERT_Dataset/processed_data.csv`
10. Now you may open and run the notebook in **Google Colab**

The notebook will automatically load the dataset from this location after mounting Google Drive.

## Notebooks

We included two versions of the notebook for your reference:

- **WithChunkingAndStratify.ipynb** 
  - Stratified Sampling
  - Chunking of emails
  - BERT training 

- **NoChunkingAndRandom.ipynb**
  - Displays preprocessing output 
