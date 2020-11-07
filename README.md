# KNN-nearest-neighbors
The purpose of this is to understand the classification capabilities of KNN to classify documents based on the term-document matrix. The term document matrix contains terms as the rows and the document as the columns. The details of each of the measures performed are documented within the associated Jupyter Notebook.

In the file, there are two versions of the classifer that are used to predict the classification:

The first is a KNN function (built from scratch using Python libraries Pandas and Numpy) that allows the user to input the Euclidean Distance measure or the Cosine Similarity measure. The Euclidean Distance Measure is also known as the pythogrean theorem which evaluates distance in a linear space and will provide the distance measure between two points. Comparatively, the Cosine Similarity measures the how similar a point in the vector space is another. In order to calculate the distance using the cosine similarity, we need to substract the similarity value from 1.

The second is KNN function from ScikitLearn library which is optimized to run at a much quicker pace. The performance between the two functions can be see as the code is executed. The conclusion however is very similar.

The data is also separated into training and test data which then is split randomly to first train the model and then test the performance.
