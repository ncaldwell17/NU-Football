<h3 style="text-align:center; color:white;"><i>Noah Caldwell-Gatsos</i></h3>
<h3 style="text-align:center; color:white;"><i>Vamsi Banda</i></h3>
<h3 style="text-align:center; color:white;"><i>Eric Yang</i></h3>

<h1 style="text-align:center;">Applying Machine Learning Strategies to Football Analytics</h1>

<h2 style="text-align:center;"><i>Northwestern University</i></h2>
<h2 style="text-align:center;"><i>Machine Learning Fall Semester 2018</i></h2>

![background](https://raw.githubusercontent.com/ncaldwell17/ncaldwell17.github.io/master/_source/_images/background.jpg)


<h2 style="text-align:center;"><i>ABSTRACT</i></h2>

<h3 style="text-align:center;"><u>Background</u></h3>
<p style="text-align:center;">After talking with Northwestern Football, we realized they currently are not using data to drive high-level decisions. In hopes to change this, we wanted to ease into this transition and work on a project that did not threaten the coaches in any way, while still providing analyses they can easily understand and trust. As a result, our project involves using play-level data to determine which attributes are the most important and influential to the outcome of football games. With this information, we can inform the NU football team on what aspects of the game they should be focusing on the most.</p>

<h3 style="text-align:center;"><u>Our Approach</u></h3>
<p style="text-align:center;">We sourced our data from profootballfocus.com which provides play-level data for all college football games. In order to keep the model as relevant as possible for Northwestern, we first limited the data to games within the BIG10 conference and only used games from 2014 and on. We wanted the model to be specific to the play-styles and trends of the BIG10. And because our end goal is to be able to provide specific features that are most important for victory, we could not use any black-box models. We also want to provide thresholds for the continuous features that change the outcome of the game. Given these constraints, we started with the following models: ZeroR, Decision Tree, Random Forest, Logistic Regression Classifier, Support Vector Machine, K-Nearest Neighbor, and Gradient Boosting Classifier.</p>

<h3 style="text-align:center;"><u>Results</u></h3>
<p style="text-align:center;">We found that Random Forest and Gradient Boosting classifiers provided the best training and test accuracies of 85% approximately. The results of the other models we tried included:</p>

![table_one](https://raw.githubusercontent.com/ncaldwell17/ncaldwell17.github.io/master/_source/_images/Screen%20Shot%202018-12-11%20at%203.50.22%20PM.png)

<p style="text-align:center;">Analyzing the Random Forest model, we were able to rank the attributes in order of importance.</p>

```Figure 1: Feature Importance```
![figure_one](https://raw.githubusercontent.com/ncaldwell17/ncaldwell17.github.io/master/_source/_images/Importances.png)


