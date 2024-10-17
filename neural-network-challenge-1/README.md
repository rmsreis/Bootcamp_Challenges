# Student Loan Risk with Deep Learning

This project uses deep learning techniques to analyze and predict student loan risk. It employs a neural network model to process various student and loan-related features to assess the risk associated with student loans.

## Installation

To run this project, you need to have Python installed along with the following libraries:
- pandas
- tensorflow
- scikit-learn
- seaborn
- matplotlib

## Usage

The main analysis is contained in the Jupyter notebook `student_loans_with_deep_learning.ipynb`. To use this project:

1. Clone the repository
2. Ensure you have the required dependencies installed
3. Open and run the Jupyter notebook

## Features

- Data preprocessing and exploration of student loan data
- Implementation of a deep learning model using TensorFlow
- Evaluation of model performance using various metrics
- Visualization of results including confusion matrix

## Data

The project uses a dataset named `student-loans.csv`. This dataset includes various features related to student loans, such as:

- Payment history
- Location parameter
- STEM degree score
- GPA ranking
- Alumni success
- Study major code
- Time to completion
- Finance workshop score
- Cohort ranking
- Total loan score
- Financial aid score
- Credit ranking

## Model

The deep learning model is built using TensorFlow and Keras. It's a sequential model with multiple dense layers, designed to predict loan risk based on the input features.

## Results

The model's performance is evaluated using classification metrics and visualized using a confusion matrix. Detailed results and analysis can be found in the notebook.

## Contributing

Contributions to this project are welcome. Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.