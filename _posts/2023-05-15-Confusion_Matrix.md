#Confusion Matrix 
Using aconfusion matrix to analysis a classifers data is super valueable. After training my classifer to identify 10 unique animals, I can than use 10 images of these animmals to test it. This will result in the a probability of what animal the image is, where the highest probabilty is the animal the classifer will choose. The idea of using a confusion matrix is that if the classifier is trained perfectly the identity matrix will be formed, where the image given perfectly matched the image. 

An exmpale of this can be showed below, 

-----------------------------
     A     B     C
     
A    1     0     0

B    0     1     0 

C    0     0     1

---------------------------
Taking the first row as an example, this shows the probability of A is A is 1 (or 100%) as well that the probability of A being B is 0 and A being C is 0. This is an example of a perfectcly trained classifier. 

