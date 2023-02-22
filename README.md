Unfortunately i cannot upload the dataset because of its size.
The dataset contains pictures from a large variety of people. We take 10 random persons and from each one we take 50 random photos.
We convert the RBG values of each pictureto one value with this fomula 0.299 * Red + 0.587 * Green + 0.114 * Blue. 
So we have a 500x4096 matrix for each picture. Then, we use pca to reduce the dimensions to 100,50 & 25.
We implement the 2 algorithms from sk-learn library and use them for the classification.
The evaluation of the algorithms  is done with F-Measure and Purity score.

