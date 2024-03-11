# TicTacToe Machine Learning Project
Introduction
In this project, I implemented and evaluated machine learning models to classify Tic Tac Toe
game outcomes and predict optimal moves. Utilizing datasets for final board states, single
moves, and intermediate states, I applied classifiers and regressors to understand their predictive
capabilities in this context.

Implementation Details
I used KNeighborsClassifier, SVC, and MLPClassifier for classification tasks, targeting final
board states and single moves. For regression on intermediate board states, I employed
KNeighborsRegressor, a custom LinearRegressionNE model based on normal equations, and
MLPRegressor. Data normalization was crucial, achieved through StandardScaler, to
preprocess the features for optimal model performance.

Evaluation Results
Classifiers on tictac_final:
• KNN Classifier excelled with an accuracy of 99.58%, indicating nearly perfect
classification.
• SVC also performed well, achieving an accuracy of 98.33%.
• MLP Classifier showed a strong accuracy of 98.43%, comparable to SVC.
Classifiers on tictac_single:
• KNN Classifier's performance dipped slightly with an accuracy of 91.86%.
• SVC's accuracy decreased significantly to 76.13%.
• MLP Classifier remained robust with an accuracy of 97.18%.
Regressors on tictac_multi:
• KNN Regressor had an accuracy of 85.76%, a solid performance for a regression task.
• Linear Regression showed lower performance with an accuracy of 76.32%.
• MLP Regressor stood out with an impressive accuracy of 97.44%, suggesting it
effectively captured the dataset's complexity.
The MLP models consistently displayed strong performance across different tasks and datasets,
likely due to their ability to model nonlinear relationships effectively.
Running the Code
To execute the project, one should run the Jupyter Notebook cells sequentially, ensuring all
dependencies are installed. The Tic Tac Toe game can be played by running the specific section
of the notebook designed for game simulation against the trained MLP model.
Challenges and Insights
Implementing the Linear Regression using normal equations was particularly challenging but
rewarding, as it deepened my understanding of the underlying mathematical principles.
Adjusting models to handle different datasets highlighted the importance of feature scaling and
parameter tuning. The project underscored the robustness of MLP models in dealing with
complex patterns and noise in data.
