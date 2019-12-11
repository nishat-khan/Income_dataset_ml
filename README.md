<center><h2>MSDS699 Final Project Repository</h2></center>

<b>Project</b>: Imcome Classification based on US 1994 Census Data

<b>Group Name</b>: cool-ml-lab

<b>Dataset</b>: This dataset is sourced from UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/Adult

<b>Steps</b>:
1) Ask
2) Acquire
3) Process
4) Model
5) Deliver

<b>Summary</b>:

Education seems to matter the most, which makes sense in real life. The more educated someone gets, the more money he/she earns. The other important factors also include relationship, age, working hours per week. This matches the real-life situation so our model makes sense. Capital-loss, race and native country are the least important features. The capital-loss has some correlation with capital-gain, so this may be the reason it shows less importance. Also, education-num column is label encoded column for column named education.


<b>Take Away</b>:
* It’s important to balance data. Upsampling works better than downsampling.
* Feature engineering matters because some feature columns can affect the model in a negative!
* Logistic regression can usually serve as a baseline for other models.
* Grid search can present the best hyperparameters but it is super slow.
* Random search works much better than a grid search in terms of the speed at a little cost of the model performance.
