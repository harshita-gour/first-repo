Digit Recognition (Number '2' Detector)
This project is a simple Machine Learning application that uses the MNIST dataset to identify handwritten digits. Specifically, I have built a binary classifier that can detect whether a given handwritten image is the number 2 or not.

Project Overview :
In this project, I used Scikit-Learn to fetch data, Matplotlib to visualize it, and a Logistic Regression model to perform the classification. This is a great entry-level project for understanding how data is processed and how models are trained.

The code follows a step-by-step approach as shown below:

	1. The initial data fetching using fetch_openml to load the MNIST dataset.

	2. Reshaping a 1D array into a 28x28 image to visualize the digit '2'.

	3. Covering the data splitting (Training set vs. Test set) and shuffling the data using numpy.

	4. Creation of the labels (Target: Is it a 2?) and fitting the LogisticRegression model.

	5. Displaying the final prediction and the accuracy score using Cross-Validation.

Technologies Used :
Python: The core programming language.

Jupyter Notebook: For interactive coding and visualization.

Scikit-Learn: For the machine learning model and data handling.

NumPy: For array manipulation and shuffling.

Matplotlib: For plotting and displaying the digit images.

How it Works
Data Loading: We load 70,000 images of handwritten digits.

Visualization: We convert the raw data into a 2D image to see what the machine "sees."

Preprocessing: We split the data so the model has "unseen" data to test its accuracy later.

Model Training: We use Logistic Regression to learn the patterns of the number '2'.

Evaluation: We use a cross_val_score to check how accurate our model is across different parts of the data.

Results:
The model achieved an accuracy of approximately 95.6% during cross-validation, meaning it is very effective at identifying the digit '2' among other numbers.
