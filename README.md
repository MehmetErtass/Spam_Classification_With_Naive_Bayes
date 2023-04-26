# Spam-Classification
* Importing necessary libraries like numpy, pandas, matplotlib, seaborn, and warnings.
* Reading the 'spam.csv' file containing SMS messages and labels as spam or ham using pandas read_csv function.
* Dropping the null values from the dataset.
* Renaming the column names as 'label' and 'message.'
* Creating a count plot to visualize the imbalance in the dataset between spam and ham messages.
* Handling the imbalanced dataset by oversampling spam messages in the dataset using for loop.
* Creating another count plot to visualize the balance between spam and ham messages after oversampling.
* Creating a new feature called 'word_count' containing the number of words in each SMS message.
* Plotting a distribution plot for word count for spam and ham messages separately.
* Creating another feature called 'contain_currency_symbol' to check if an SMS message contains a currency symbol or not.
* Creating a count plot to visualize the number of SMS messages containing currency symbols for spam and ham messages separately.
* Creating another feature called 'contain_number' to check if an SMS message contains a number or not.
* Creating a count plot to visualize the number of SMS messages containing numbers for spam and ham messages separately.
* Importing necessary libraries like nltk, re, and stopwords.
* Cleaning the SMS messages using the WordNetLemmatizer, removing special characters, converting them to lowercase, tokenizing them, removing stop words, and lemmatizing them.
* Creating a bag of words model using the TfidfVectorizer, extracting independent and dependent variables from the dataset.
* Splitting the dataset into training and testing sets using the train_test_split function.
* Fitting the Naive Bayes model to the training set and calculating the average F1 score and standard deviation using the cross_val_score function.
* Generating a classification report and confusion matrix for the Naive Bayes model using the classification_report and confusion_matrix functions, respectively.
