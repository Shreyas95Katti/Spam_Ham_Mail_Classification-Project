# Spam_Ham_Mail_Classification-Project

Hello guys!!!

The spam ham mail detection project is a classification problem. We classify a given input mail body into spam mail or ham mail based of the contents. This project uses the feature extraction function TfidfVectorizer which allows us to covert text based inputs to vectors thus making it easy to apply for the regression model.

The project begins with importing various required libraries and loading our dataset. We observe that there are few null values in the dataset so we go ahead with data cleaning. Further we encode "spam" and "ham" as 0 and 1 respectively, again it is done to reduce our work with strings. The next step involves splitting the dataset into feature matrix and target matrix which is again further split into training and testing matrices. Now we use the function TfidfVectorizer on the feature matrix to covert text to numbers helping us to feed these values into the logistic regression model. We finally come down to the main machine learning model. We follow the basic machine learning model steps 1)Define the model 2)Fit the model 3)Training the model 4)Testing the model 5)Checking accuracy scores for both. To finish off I have created a user friendly interface which allows you to enter a mail body of your choice and the model predicts if it is a Ham mail or a Spam mail. This project is highly beginner friendly so I would appritiate all my Machine Learning enthusiasts to have a look at this

Dataset: https://drive.google.com/file/d/1uzbhec5TW_OjFr4UUZkoMm0rpyvYdhZw/view

# Happy Learning!
