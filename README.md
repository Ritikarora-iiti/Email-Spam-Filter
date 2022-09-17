# Email-Spam-Filter

This project aims to categorise emails as spam or anti-spam (Ham). I used the Support Vector Machine (SVM) Machine Learning Model to predict whether the email was spam or not.
All the source code are present in my GitHub repository.

Steps :

1. Download the emails dataset and copy all the emails from into a folder named "emails" which should be presented at the same place where these codes are. The data consists of around 10k emails.
2. Now, run the code extracting_unique_words_from_all_emails.py which helps to make file wordslist.csv which contains the words found in emails which occur more than or equal to 100 times in all emails.It gives us a file of common words.
3. Now, run processing_emails_to_find_occurance_of_words.py to find the occurance of each word in the emails dataset and make frequency.csv file which stores the frequency of each important word present in wordlist.csv in every email.
4. Finally run the svm_implementation.py code to study the predicted results of Support Vector Machine Algorithm on the dataset.
