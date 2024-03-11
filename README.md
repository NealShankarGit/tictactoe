# TicTacToe Machine Learning Project
**Introduction**<br>
In this project, I implemented and evaluated machine learning models to classify Tic Tac Toe
game outcomes and predict optimal moves. Utilizing datasets for final board states, single
moves, and intermediate states, I applied classifiers and regressors to understand their predictive
capabilities in this context.

**Implementation Details**<br>
I used KNeighborsClassifier, SVC, and MLPClassifier for classification tasks, targeting final
board states and single moves. For regression on intermediate board states, I employed
KNeighborsRegressor, a custom LinearRegressionNE model based on normal equations, and
MLPRegressor. Data normalization was crucial, achieved through StandardScaler, to
preprocess the features for optimal model performance.

**Evaluation Results**<br>
Classifiers on tictac_final:<br>
• KNN Classifier excelled with an accuracy of 99.58%, indicating nearly perfect
classification.<br>
• SVC also performed well, achieving an accuracy of 98.33%.<br>
• MLP Classifier showed a strong accuracy of 98.43%, comparable to SVC.
Classifiers on tictac_single:<br>
• KNN Classifier's performance dipped slightly with an accuracy of 91.86%.<br>
• SVC's accuracy decreased significantly to 76.13%.<br>
• MLP Classifier remained robust with an accuracy of 97.18%.<br>
Regressors on tictac_multi:<br>
• KNN Regressor had an accuracy of 85.76%, a solid performance for a regression task.<br>
• Linear Regression showed lower performance with an accuracy of 76.32%.<br>
• MLP Regressor stood out with an impressive accuracy of 97.44%, suggesting it
effectively captured the dataset's complexity.<br>
The MLP models consistently displayed strong performance across different tasks and datasets,
likely due to their ability to model nonlinear relationships effectively.

**Running the Code**<br>
To execute the project, one should run the Jupyter Notebook cells sequentially, ensuring all
dependencies are installed. The Tic Tac Toe game can be played by running the specific section
of the notebook designed for game simulation against the trained MLP model.
