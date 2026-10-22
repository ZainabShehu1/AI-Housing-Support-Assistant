AI Housing Support Assistant

An independent Python and machine-learning portfolio project exploring automated classification of housing-support enquiries.

Project Overview

This project investigates how natural-language processing (NLP) and supervised machine learning could help categorise fictional housing-support enquiries into four categories:

* Repairs and maintenance
* Potential safety concerns
* Financial support
* General housing enquiries

The aim was to explore how AI might support administrative workflows while highlighting the importance of testing, model evaluation and human oversight.

Technologies Used

* Python: Programming and data processing
* pandas: Organising and analysing enquiry data
* matplotlib: Visualising enquiry categories
* scikit-learn: Building and evaluating machine-learning classifiers
* TF-IDF: Converting text into numerical features
* Logistic Regression: Supervised text classification
* Google Colab: Cloud-based development environment
* GitHub: Version control and project documentation

Development Process

1. Rule-based prototype

Developed an initial classifier using Python functions, conditional statements and keyword matching.

2. Testing and debugging

Created test cases to identify limitations in keyword-based classification. Improved the rule-based algorithm and compared its performance on selected examples.

3. Machine-learning implementation

Trained a supervised text classifier using TF-IDF and logistic regression on 24 fictional labelled enquiries.

4. Model evaluation

Evaluated the model using classification accuracy, precision, recall and F1-score. The initial machine-learning model achieved 87.5% accuracy on an eight-example evaluation set.

5. Model iteration

Expanded the training dataset from 24 to 34 examples after identifying a misclassified potential safety concern.

On a subsequent 12-example exploratory test set:

Metric	Original model	Updated model
Accuracy	91.7%	58.3%
Safety-related recall	100%	100%

The results demonstrated that increasing the quantity of training data does not necessarily improve overall model performance. The original machine-learning model was retained as the final demonstration prototype.

Key Learning Outcomes

This project strengthened my understanding of:

* Python programming and structured problem-solving
* Data preparation and exploratory analysis
* Supervised machine learning and natural-language processing
* Training and evaluating classification models
* Error analysis and iterative development
* Responsible AI and the importance of human oversight

Limitations and Future Improvements

This is an educational prototype developed using a small, entirely fictional dataset. Its evaluation results are not representative of real-world performance.

Future improvements would include a larger, more diverse dataset, formal training/validation/test separation, additional classification algorithms and further evaluation of false positives and false negatives.

This project must not be used to evaluate real housing emergencies or make decisions about people’s safety.

Running the Project

Open the AI_Housing_Support_Assistant.ipynb notebook in Google Colab and select Runtime → Run all to execute the analysis and model demonstrations.

The project uses Python libraries available in the Google Colab environment.
