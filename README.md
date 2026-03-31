Student Performance Predictor
This is a machine learning project that tries to figure out if a student will Pass or Fail. It looks at how hours they study how often they attend class and how they did on their last exam.

I made this project as part of my ai ml course.
What This Project Does
It makes a list of 300 students and their information.

It creates three charts to help us understand the data. One chart shows how many students passed or failed another shows how hours they studied and the last one shows how all the information is related.

It tries out three machine learning models to see which one works best. The models are called Logistic Regression, Decision Tree and Random Forest.

It picks the model and saves a chart to show how well it works.

It saves the model so we can use it again later.

It lets us enter information about a student and predict whether they will Pass or Fail.

How to Run
Step 1. Get the libraries

You need to install some libraries to run this project. You can do this by running the following command:


pip install -r requirements.txt

Step 2. Run the project

Now you can run the project by typing:


python main.py

That is all you need to do. The project will run with one command.

Files

main.py            ← this is the file for the project

requirements.txt   ← this file lists the libraries we need

students.csv       ← this is the list of students (it's made automatically)

charts/            ← this is where the charts are saved (they are made automatically)

model/             ← this is where the machine learning models are saved (they are made automatically)

Example Output

[Step 4] Training and comparing models...

Model                   Accuracy   CV Score

--------------------------------------------

Logistic Regression       86.67%     85.21%

Decision Tree             88.33%     87.10%

Random Forest             91.67%     90.43%

The best model is Random Forest.

The accuracy of the model is 91.67%.

Interactive Predictor
After the project is done running you can enter information about a student to see if they will Pass or Fail:


How hours does the student study, per day (1–9): 6

What is the students attendance percentage (40–100): 85

What was the students previous score (0–100): 72

The result is: ✅ PASS

The confidence is: Pass = 88.0%  |  Fail = 12.0%

Technologies Used
I used Python 3 to make this project.

I used the pandas and numpy libraries to handle the data.

I used the scikit-learn library to make the machine learning models.

I used the matplotlib and seaborn libraries to make the charts.

The Student Performance Predictor project uses these technologies to predict whether a Student Performance Predictor will Pass or Fail.
