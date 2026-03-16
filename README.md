the dataset can be downloaded from Kaggle
https://www.kaggle.com/datasets/rishabhkausish/reddit-depression-dataset

This notebook can be run in colab
The dataset can be put in Google Drive in the following folder
My Drive/AIHC/data
If the folder is different change the same in notebook

while running the code cells I have saved intermediate results in corresponding csvs along with the embeddings

So for example if cell no 4 we read reddit_depression_dataset.csv and do strucure and data cleanup, we then are saving the result 
df.to_csv('optimized_reddit_depression_data.csv', index=False)

Likewise for all important extractions and adding new columns to dataframe the resultant data is saved, so the processing can be done post that
So we dont need to rerun the same cleanup process again. this saves time and resources.

