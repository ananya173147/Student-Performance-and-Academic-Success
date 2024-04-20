# Voting Classifier Algorithm for Student Performance and Academic Success
Source code for [Prediction of Student’s Performance and Academic Success.](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)   
Group Members: Ananya Mantravadi (amantra), Nainisha Bhallamudi (nbhalla), Pavithra Velumani (pveluma)

## Dataset
Created from a higher education institution (acquired from several disjoint databases) related to students enrolled in different undergraduate degrees, such as agronomy, design, education, nursing, journalism, management, social service, and technologies. The dataset includes information known at the time of student enrollment (academic path, demographics, and social-economic factors) and the students' academic performance at the end of the first and second semesters. The data is used to build classification models to predict students' dropout and academic sucess. The problem is formulated as a three category classification task, in which there is a strong imbalance towards one of the classes.

## Experimental Settings
**Train Test Split**: The dataset is divided into Training and Test sets with an 80% and 20% split.   
**Repeated Stratified K-Fold Cross-Validation**: Used due to class imbalance. 10 Folds: Each fold maintains class proportions. Repeated thrice and took the mean of them

## Final Model
Voting Classifier Ensemble: Adaptive Boosting with Random Forests and eXtreme Gradient Boosting (Soft Voting)

## Setup
Run and install required libraries through requirements.txt. Execute Python notebook cell by cell to reproduce the results. We used a random seed of 42 for all our experiments.

## Results
![res](https://github.com/ananya173147/Student-Performance-and-Academic-Success/assets/59045952/5288f83b-a50e-42ae-a62a-6194c407b3cb)

