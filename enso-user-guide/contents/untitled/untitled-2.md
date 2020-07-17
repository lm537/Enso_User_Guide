# 2.3 Viewing and Managing Multiple Versions of the Models in Model Studio

·       Model selection is the process of choosing one among many candidate models for a predictive modeling problem.

·       Production Model Monitoring identifies issues with model performance that lead to retraining the model on newer data.

·       A model created in Enso will have a certain accuracy percentage.

·       Training the model with the help of training data and by assisted extraction increases the overall accuracy of the model.

·       Enso provides this feature of training and re-training the model in model studio to enhance the accuracy percentage of the model.

Steps involved:

      1.          Go to Model Studio in the Enso Canvas Platform.

![](../../../.gitbook/assets/image%20%2863%29.png)

2. Select any model from the list. A base version of the model will be displayed as shown below.

![](../../../.gitbook/assets/image%20%28174%29.png)

Here the confusion matrix compares the various values for each target class \(TP, TN, FP, FN\)

      3. Click on the base version and select Train.

![](../../../.gitbook/assets/image%20%2824%29.png)

4. Select the Dataset you wish to train the model for and click on “Train Model”.

![](../../../.gitbook/assets/image%20%28127%29.png)

5. Click on Evaluate.

![](../../../.gitbook/assets/image%20%28190%29.png)

6.  Select the particular Dataset you want to evaluate the model for and click on “Evaluate Model”.

![](../../../.gitbook/assets/image%20%285%29.png)

7. Once the model is trained and evaluated the new version will appear as shown below.

![](../../../.gitbook/assets/image%20%28152%29.png)

Here we can see the Confusion Matrix given for various instances.

The graph depicts the overview of the versions which shows the accuracy of the versions.

As we can see in the screenshot above the letter “R” represents the system recommended version. \(However we can use the version based on our requirement parameters.\)

The other parameters that are considered are “Weighted Precision”, “Weighted Recall” and “Weighted F1”

8. Select the version of the model based on the required parameters and click on Publish Version.

![](../../../.gitbook/assets/image%20%2837%29.png)

9. Once the version is published, enable the newly published version and you can set the new published version as default.

![](../../../.gitbook/assets/image%20%28136%29.png)

