# Term-Project-PPE-Detection-using-YOLOv8n
This project purpose is for NTU Deep Learning and Computer Vision class final individual project. The goal of this project is to be able to detect PPE (Personal protective equipment) in 3 different classes including of helmets, vests, and heads.

1. Please check Dataset file for how to download Dataset

2. There are 2 models --> model.ipynb and model2.ipynb
      2.1 It is recommended to start with model2.ipynb and run this code on kaggle server after downloading the dataset in
          kaggle.This model is specifcially just for MODEL TRAINING, it is not able for testing, testing evaluation, and video
          detection. Again, this code is for training model on "Kaggle Server" which is recommended to save time as GPU P100
          is designed specially for computation
      2.2 For model.ipynb, this one is for local usage. It is also possible to start Model training here but it is recommended
          to train using model2.ipynb first in kaggle server and "download" best.pt then paste it on the folder. Please ensure
          that the file name is correct, if you change file name to best1.pt for repetitive problem, please change the weight
          path. If best.pt exist (weight path exist), the code will skip training and use the provided weight (best.pt)

3. For running the model on testing data, evaluation, graph plotting, video detection, it is in model.ipynb which is
   recommended for running on local. For video, you can download any construction site footage video from internet maybe from
   https://www.pexels.com/search/videos/construction/

4. For results file, it is generated when you train the model. The .png file is generated when you run the whole evaluation on
   model.ipynb as for ex3 and ex4 is just the example from video detection.

   
