# Dog_Cat_Sound_Classifier

A cat and dog sound classifier model. Features were extracted using the librosa library, making the dataset. After some basic preprocessing, augmenting and exploratory data analysis, various classification models were applied. The models with highest accuracy were analysed to see where they were showing incorrect classifications. It was found that the XG Boost model performed the best, and made mistakes only when there was external disturbance in the input dog/cat sound, such as noises of humans, utensils and so on.
