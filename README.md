# Project
ARTIFICIAL INTELLIGENCE SEMESTER PROJECT


Kaggle Submission Images:
![image](https://user-images.githubusercontent.com/61775133/147608336-9940619f-bfd1-4313-b1b2-87cf33a626fa.png)
![image](https://user-images.githubusercontent.com/61775133/147608366-6459b14c-8f2a-4e4c-8813-a7b36d228345.png)

**How you approach the task?**
We first go through the documentation of scikit-learn documentation. We first observe that what are multiclasses then we selected multiple classifiers according to our data set
requirement and used the best 4 classifiers for training our 8 models. We researched about the project to fulfil the requirements. We have made multiple submmissions on kaggle and
tried our best to acheieve highest accuracy and for achieving this accuracy we have tweak our classifiers by adjusting thier parameters.

**Which models you selected and why?**
**Decision Tree Classifier**
we used this classifier because it is able to handle both numerical and categorical data. However scikit-learn implementation does not support categorical variables for now. Other techniques are usually specialised in analysing datasets that have only one type of variable. See algorithms for more information.
Also it ables to handle multi-output problems

**Bagging Classifier**
We used this classifier because It provides stability and increases the machine learning algorithm's accuracy that is used in statistical classification and regression. It helps in reducing variance.

**Extra tree Classifier**
We used this classifier because it used average and to improve the predictive accuracy and control over-fitting.

**Ridge Classifiers**
We used this classifier because  it modifies the loss function by adding the penalty (shrinkage quantity) equivalent to the square of the magnitude of coefficients.

**Random Forest Classifiers**
We used this classifier because it does not suffer from the overfitting problem. The main reason is that it takes the average of all the predictions, which cancels out the biases. The algorithm can be used in both classification and regression problems. Random forests can also handle missing values.




**Problems you faced?**
One of the main problem was that our dataset had NAN values in 3 columns so we dropped them to make the accurracy higher then we had another major problem of normalizing our training data so we met our teacher Mr. Farooq who had guided us in how to normalize data. After this meeting our problem got solved. 

**Refrences you used?**
Refrences
https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier
https://scikit-learn.org/stable/modules/generated/sklearn.tree.ExtraTreeClassifier.html#sklearn.tree.ExtraTreeClassifier
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#sklearn.ensemble.RandomForestClassifier
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeClassifier.html#sklearn.linear_model.RidgeClassifier
https://www.ttested.com/removing-zero-variance-columns/
https://stackoverflow.com/questions/20209600/pandas-dataframe-remove-constant-column
