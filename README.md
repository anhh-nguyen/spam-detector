# spam-detector
A spam detector using machine learning to classify emails into spam and non-spam.

## Data
spam.csv mimics the layout of a typical email inbox and includes over 5,000 examples that will be used to trained our model

## Procedure
I used train-test split method to train our spam detector. The train-test split is a technique for evaluating the performance of a machine learning algorithm that involves taking a dataset and dividing it into two separate datasets
1. Train dataset: used to fit the machine learning model
2. Test dataset: used to evaluate the fit of the machine learning model

I extracted the data using ```CountVectorizer()``` function. ```CountVectorizer()``` randomly assigns a number to each word in a process called tokenizing. Then, it counts the number of occurrences of words and saves it.
![Screen Shot 2022-07-20 at 1 13 25 AM](https://user-images.githubusercontent.com/90353674/179902009-f467c468-5165-4975-b135-21b7faeead04.png)

I built a machine learning model using support vector algorithm. The algorithm creates a line, or a hyperplane, which separates the data into classes. SVM can solve both linear and non-linear problems

The detector was able to classify spam with 98% accuracy
![Screen Shot 2022-07-20 at 12 57 25 AM](https://user-images.githubusercontent.com/90353674/179902376-94f2577e-f73a-4fc1-89e1-f3036f38b239.png)

## Build
Run the following commands to install dependencies
```
pip3 install wheel
pip3 install pandas
pip3 install -U scikit-learn
```



