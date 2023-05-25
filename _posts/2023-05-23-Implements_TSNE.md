# Implementing TSNE 

Through some research I discovered how I can implement a TSNE into my classifer code!! Through my research I discoverd this [github repository](https://github.com/suredie/FastAI-Examples/tree/master). In this, the author has an example classifer similar to the two classifiers I've built for this assignment. He has also implemented a TSNE to anaylsis his results! Using this as a guide I managed to build my own TSNE. 

By using a method to save the predictions of each image given to my model, and whether or not it is true. I managed to convert each data entry to a corresponding location. I then managed to give the data point a colour depending on what catagory it was under and then plotted it on a scatter plot. 

Here is an exmaple from Q2, the animal classfier. 
![Animal classifier TSNE](/images/TSNEq2.png)

From this, it can be seen that each data catagory will have it's own "section". This shows that the classifier will group these together, showing it's accuracy when prediciting. Isn't that just so cool!!! Much better alternative then reading a bunch of meaningless numbers!!
