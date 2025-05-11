# Analyzing Employee Job Satisfaction through Sentiment Analysis for Enhanced Workplace Improvement and Business Success
![image](https://github.com/user-attachments/assets/18b62b0b-e4a9-4bd5-9c4a-50c9f8b1d4e1)

# 🚀 Usage
Load the raw data
Open Data/answers.xlsx to review the questionnaire responses.

# Preprocess text

Run Preprocess/preprocess_for_Lexicons.ipynb to clean, tokenize, and normalize employee responses and the results of salary, working environment and superiors.
Use Preprocess/preprocess_Lexicon_workOO.ipynb  to clean, tokenize, and normalize employee responses on overall work entity and the results.
Handle multiple-choice items
Execute Preprocess/Multiple-Choice-Question.ipynb a bar plot for multiple choice results.

# Perform sentiment analysis
Apply lexicon-based sentiment scoring using provided dictionaries under Dictionaries/:
Dictionary of Satisfaction (DoS)
Dictionary of Work (DoW)
Dictionary of Superiors (DoSp)

# Negations, suffixes, tones, and stopwords
Analyze results
Aggregate sentiment scores and visualize trends to identify positive, neutral, and negative sentiment distributions across key domains.

# 🗂️ Dictionaries & Lexicons

DoS.txt / DoSP.txt: Dictionary of superiors-related terms and their polarity.
DoW.txt / DoWE.txt: Dictionary for Working environment-related terms and environment descriptors.
Negations.txt: Words that invert sentiment.
Useless_words.txt: Words to be removed during preprocessing.
suffixes.txt: Common word endings for stemming.
tones.txt: Markers in greek language.



# 📈 Example Workflow

Clean and tokenize text, adjust tokens (negations, suffixes) with the preprocess_for_Lexicons.ipynb/in preprocess_Lexicon_workOO.ipynb. notebook.
