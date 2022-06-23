# Predicting-whether-a-given-tweet-is-about-a-real-disaster-or-not
The purpose of the project was to determine from tweets (which are microblogs with a limit of 280 characters only) whether it was pointing towards an actual disaster or not. As part of Exploratory Data Analysis, identified missing values &amp; unique values and Tweet distribution &amp; cardinality with respect to keywords; handled meta-features; showed target class distribution; found out Unigrams, Bigrams and Trigrams. As part of feature engineering, tweet cleansing, checking of vocabulary and text coverage pre-cleaning vs post-cleaning and detection/correction of mislabeled tweets were done. Random Test-train split and cross validation were done before model training. BERT was used because it is designed to help computers understand the meaning of ambiguous language in text by using surrounding text to establish context. BERT, which stands for Bidirectional Encoder Representations from Transformers, is based on Transformers, a deep learning model in which every output element is connected to every input element, and the weightings between them are dynamically calculated based upon their connection. Parameters such as lr (learning rate), epochs (the number of epochs is a hyperparameter of gradient descent that controls the number of complete passes through the training dataset) and batch_size (the batch size is a hyperparameter of gradient descent that controls the number of training samples to work through before the model’s internal parameters are updated) were used for controlling the learning process. The BERT author’s recommended values were used for these parameters. 10 times randomly data splitting was done and for each splitting, model was run, then the average accuracy and F1-score were calculated from the 10 runs. The average Accuracy Score and F1 scores were 86.59% and 0.83 respectively.
