# Spam Ham Mail Classification Project
Hello guys!!!

The spam ham mail detection project is a classification problem. We classify a given input mail body into spam mail or ham mail based on the contents. This project uses the feature extraction function TfidfVectorizer, which allows us to convert text-based inputs to vectors, thus making it easy to apply for the regression model.

The project begins with importing various required libraries and loading our dataset. We observe that there are a few null values in the dataset, so we proceed with data cleaning. Further, we encode "spam" and "ham" as 0 and 1 respectively, to reduce our work with strings. The next step involves splitting the dataset into a feature matrix and a target matrix, which is further split into training and testing matrices. We then use the function TfidfVectorizer on the feature matrix to convert text to numbers, allowing us to feed these values into the logistic regression model.

We follow the basic machine learning model steps:

1. Define the model
2. Fit the model
3. Train the model
4. Test the model
5. Check accuracy scores for both training and testing

To finish off, I have created a user-friendly interface that allows you to enter a mail body of your choice, and the model predicts if it is a Ham mail or a Spam mail. This project is highly beginner-friendly, so I would appreciate all my Machine Learning enthusiasts to have a look at this.

Dataset: https://drive.google.com/file/d/1uzbhec5TW_OjFr4UUZkoMm0rpyvYdhZw/view

# Happy Learning!
