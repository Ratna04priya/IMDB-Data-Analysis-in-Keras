# IMDB-Data-Analysis-in-Keras
## Analyzing IMDB Data in Keras
_IMDB data is preloaded in keras, and can be analysed by  performing basic model operations on the dataset. 
The dataset is already preprocessed so we have an advantage over it._

## About the Project
It is one of the most basic and practiced techniques in keras. Just an experimental and basic repository while practicing the baby steps in keras. 
Here, six basic steps are involved,
### 1. Loading the IMDB data from keras
This dataset comes preloaded with Keras( _Keras.datasets_), so one simple command will get us training and testing data. There is a parameter for how many words we want to look at. We've set it at 1000, but feel free to experiment.

### 2. Examining the data
The data has been already pre-processed, where all the words have numbers, and the reviews come in as a vector with the words that the review contains. For example, if the word 'the' is the first one in our dictionary, and a review contains the word 'the', then there is a 1 in the corresponding vector.

The output comes as a vector of 1's and 0's, where 1 is a positive sentiment for the review, and 0 is negative.

### 3. One-hot encoding the output
Here, we'll turn the input vectors into (0,1)-vectors. For example, if the pre-processed vector contains the number 14, then in the processed vector, the 14th entry will be 1.

### 4. Building the model architecture
Build a model here using sequential. Feel free to experiment with different layers and sizes! Also, experiment adding dropout to reduce overfitting.

### 5. Training the model
Run the model here.

### 6. Evaluating the model
This will give you the accuracy of the model, as evaluated on the testing set. 

