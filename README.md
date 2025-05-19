# SPAM Detection Using BERT

## Setup Instructions (Google Drive)

1. Go to [https://drive.google.com](https://drive.google.com)
2. Click the **+ New** button → select **New Folder**
3. Name the folder **BERT_Dataset**, then click **Create**
4. Open the **BERT_Dataset** folder
5. Click **+ New** → select **File Upload**, then choose the dataset file:  
   **processed_data.csv**
6. Confirm the dataset has uploaded to this path:  
   `/MyDrive/BERT_Dataset/processed_data.csv`
7. Now you may open and run the notebook in **Google Colab**

The notebook will automatically load the dataset from this location after mounting Google Drive.

## Notebooks

We included two versions of the notebook for your reference:

- **WithChunkingAndStratify.ipynb** 
  - Stratified Sampling
  - Chunking of emails
  - BERT training 

- **NoChunkingAndRandom.ipynb**
  - Displays preprocessing output 
