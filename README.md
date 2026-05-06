## thesis_MER
Bence Pór 2026 CEU Data Science and Society Bachelor Thesis, Music Emotion Recognition

## To run the code yourself:
# Getting the data
First you need to get the datasets (too large to upload to github) which are also cited in the paper, but here are the links:

emotify dataset (4x100 mp3 files):
https://www.projects.science.uu.nl/memotion/emotifydata/    -download only the sound files, annotations are not necessary

kaggle music-mood-classification dataset (5x500 wav files)
https://www.kaggle.com/datasets/auliayasmin/music-mood-classification

# Runnin in Google CoLab (preferrably with T4)
I would advise you to run the notebooks in CoLab if you do not want to modify the code because of the file structure. Create a folder in your google drive. Upload the two datasets into it and the 3 jupiter notebooks (.ipynb). Create also an empty folder called 'artifacts'. The latter one is going to be necessary to save the clustering data into. After everything uploaded, run the files in this order: 
-5s
-clustering
-compare

You might need to modify file paths and names a bit, these are always located in the first few cells. To use my clusters, they are saved in the .joblib file.


