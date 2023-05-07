Download Link: https://assignmentchef.com/product/solved-ie343-midterm-project-logistic-models-applied-to-real-datasets
<br>
In this midterm project, you need to create logistic models applied to real datasets. There are two tasks for this project. Task 1 is about building a logistic regression model for a multi-class problem. In this task, the iris flower dataset is provided, and the problem is about classifying each iris data into 3 species. For the second task, you must build a binary logistic regression model for the Titanic dataset. For this dataset you need to pay attention to preprocess data for improving model accuracy. The problem is finding the survivors from the passengers. More detailed explanations of each task are in the sections below. Python is the only programming language you will be allowed to use. Also for completing code, you are not allowed to use machine learning libraries such as ‘Scikit-learn’, ‘Keras’, or ‘SciPy’. However basic libraries such as ‘NumPy’, ‘pandas’, or ‘math’ are allowed.

<ul>

 <li>Grade policy</li>

</ul>

50 points will be assigned to each task. For task 1, 50pts will be assigned to the report with your source code. For task 2, 20pts will be assign to the report and 30pts will be assign to the model accuracy. For measuring the model accuracy, the TA will run your code and get the model accuracy with a test dataset which is different from the distributed test dataset.

<strong>Task 1</strong>

<ul>

 <li>Data

  <ul>

   <li>The dataset has information of iris flower samples (training set: 104, test set: 23).</li>

   <li>Input features: sepal length, sepal width, petal length, and petal width.</li>

   <li>Target: 3 species of iris (‘iris-virginica’, ‘iris-setosa’, and ‘iris-versicolor’).</li>

  </ul></li>

 <li>Method</li>

</ul>

The logistic regression for multi-classes is called ‘multinomial logistic regression’ or ‘softmax regression’. The multinomial logistic function with parameter <em>θ </em>containing <em>θ</em><sup>(<em>j</em>)</sup>’s is represented as

<em> .                                                    </em>(0.1)

where <em>K </em>is the number of classes, <em>θ</em><sup>(<em>j</em>) </sup>is the vector parameter for the class <em>j</em>, and <em>x </em>is the input vector.

<ul>

 <li>To-Do List

  <ol>

   <li>Design a proper loss function for the multinomial logistic function and describe how to train your model parameter using a gradient descent method. Write down your formulas in detail.</li>

   <li>Complete the code in ‘./App/logistic regressor.py’ file using the model described in the Method section.</li>

   <li>Describe the code you wrote in ‘logistic regressor.py’ file line by line and write down the accuracy of your model.</li>

   <li>Is there any methods to apply binary logistic regression models to multi-class problems? Explain your ideas.</li>

   <li>You must submit your entire completed python files and a report which contains the answers of the question 1, 3, and 4.</li>

  </ol></li>

</ul>

1

<em>– Midterm Project                                                                                                                           </em>2

<strong>Task 2</strong>

<ul>

 <li>Data</li>

 <li>The dataset has information of passengers on the Titanic (train: 623, test: 134).</li>

 <li>Input features: Pclass, Name, Sex, Age, ….</li>

 <li>Target: Survivor(=1) or not(=0).</li>

 <li>You can find more details about the data via the url: <a href="https://www.kaggle.com/c/titanic/data">https://www.kaggle.com/c/titanic/data</a><a href="https://www.kaggle.com/c/titanic/data">. </a>There are some ambiguous features in the dataset. Discussions on the above url are helpful.</li>

 <li>Method</li>

</ul>

The logistic regression for binary classes must be used for this project

<ul>

 <li>To-Do List

  <ol>

   <li>Complete the codes in ‘main.py’ for data preprocessing and ‘./App/logistic regressor.py’ for a model.</li>

   <li>Describe your methods for data preprocessing. You don’t need to describe your data preprocessing code line by line but explain your ideas for data preprocessing in the report.</li>

   <li>Describe your logistic regression model with the code line by line.</li>

   <li>You must submit your entire completed python files and a report which contains the answers to question 2 and 3.</li>

  </ol></li>

</ul>