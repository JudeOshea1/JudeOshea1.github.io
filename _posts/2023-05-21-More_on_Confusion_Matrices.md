# More on Confusion Matrices 
I have discovered how to implement confusion matrices into my code automatically!! 
Using [this](https://github.com/suredie/FastAI-Examples/tree/master) github repository. I managed to analysis the example code named "Hello_World_with_FastAI". In creates a basic learner using the function "cnn_learner" and analyses the results with a confusion matrix. Through using the funciton [interpret()](https://docs.fast.ai/interpret.html) and [plot_confusion_matrix()](https://eagerai.github.io/fastai/reference/plot_confusion_matrix.html), the code will automatically produce a confusion matrix! How Cool!

I used this information to develop my own method of producing a confusion matrix through researching more fucntion and found the following to work the best.

```
interp = ClassificationInterpretation.from_learner(learn)
interp.plot_confusion_matrix()
```
Where Learn is my classificaiton model! This allowed the model to produce a confusion matrix based on the data that was spilt during the models learning phase. 
