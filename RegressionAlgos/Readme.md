# Logistic Regression
<p>Logistic regression is used to solve binary classification problems(Problems having 2 classes,Eg Predict either the e-mail is spam or not spam etc).
It's the most fundamental and computationaly efficient algorithm of machine learning.It uses the logarithmic error as its 
<a href = "https://www.analyticsvidhya.com/blog/2019/08/11-important-model-evaluation-error-metrics/">evaluation metrics</a>.</p>

<h3>Breast Cancer Dataset</h3>
<p> Its a 2 class classification problem and hence logistic regression performs well on this dataset.</p>
<h4> Instruction for Running the code </h4>
<ul>
<li>Assign the path of the dataset in the path variable.
<li>Tune the hyperparamters by initializing the appropriate values of learning_rate and no_of_iterations.
<li>Run all the cells
</ul>
<h3>Iris Dataset</h3>
<p>Its a 3 class classification problem and hence to apply logistic regression we must use the one vs all approach.
i.e Train 3 seperate regression units which will learn to identify one class respectively.And at the end combine the results.</p>
<h4> Instruction for Running the code </h4>
<ul>
<li>Assign the path of the dataset in the path variable.
<li>Tune the hyperparamters by initializing the appropriate values of learning_rate and no_of_iterations.
<li>Run all the cells
</ul>

<h5>Note: As stated in the iris-dataset one class is linearly non seperable and hence the accuracy of the model dips in this case.</h5>
