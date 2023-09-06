# predicting_strokes_neural_network

proposal:
https://docs.google.com/document/d/16ukOGunJESs9_Quxxgeypgekqe2HYuNAiKV-I8RF6X8/edit

slide deck:
https://docs.google.com/presentation/d/131vClhtjkAr21AXo5oyu0cCoQqJsgsAIEydug6axmRo/edit?usp=sharing

Resources: https://www.kaggle.com/datasets/jillanisofttech/brain-stroke-dataset
This data is pulled from UCI open-source data warehouse.

Running data_prep.ipynb is the first step. This exports a cleaned, scaled and ready for use CSV.
SQLite_Batch_File.bat in resources converts cleaned_data.csv to an sqlite file: stroke_data.sqlite.

Stroke_Neural_Network_Builder.ipynb and Stroke_Neural_Network_Visualizations.ipynb should be ran in google colab. Instructions for importing data within colab is commented in the code.
supervised_learning_model_1.ipynb can be ran in jupyter notebook.

