# ML-Based-Antivirus
We use 2 python files to perform to the classification
namely:
1. Train.py
2. Antivirus.py
Train.py uses python libraries used for ML like:
pandas, NumPy, pickle and the sklearn library.
This file then runs various ML models to identify the
best in terms of the percent of success of
classification/identification. The various algorithms
used for comparison namely are:
1. Decision Tree
2. Random Forest
3. Gradient Boosting
4. Ada Boosting
5. Gaussian Naïve Bayes
Then we proceed to display the success of all of these
algorithms then then system chooses the one with the
highest success rate. Random forest was observed to
be the most frequent winner here.
Once the training of the model is complete with the
execution of the train.py. We will proceed to run the
antivirus.py file, it contains the program meant to
perform the scanning of the uploaded file.
