# FlipItNews-Word2Vec
The Gurugram-based company ‘FlipItNews’ aims to revolutionize the way Indians perceive finance, business, and capital market investment, by giving it a boost through artificial intelligence (AI) and machine learning (ML). They’re on a mission to reinvent financial literacy for Indians, where financial awareness is driven by smart information discovery and engagement with peers. Through their smart content discovery and contextual engagement, the company is simplifying business, finance, and investment for millennials and first-time investors

# Problem Statement:

The goal of this project is to use a bunch of news articles extracted from the companies’ internal database and categorize them into several categories like politics, technology, sports, business and entertainment based on their content. Use natural language processing and create & compare at least three different models.

Context:
The Gurugram-based company ‘FlipItNews’ aims to revolutionize the way Indians perceive finance, business, and capital market investment, by giving it a boost through artificial intelligence (AI) and machine learning (ML). They’re on a mission to reinvent financial literacy for Indians, where financial awareness is driven by smart information discovery and engagement with peers. Through their smart content discovery and contextual engagement, the company is simplifying business, finance, and investment for millennials and first-time investors
Objective:
The goal of this project is to use a bunch of news articles extracted from the companies’ internal database and categorize them into several categories like politics, technology, sports, business and entertainment based on their content. Use natural language processing and create & compare at least three different models.



**Attribute Information:**
		
  • Article
  • Category
  
The features names are themselves pretty self-explanatory


**Concepts Tested:**

	• Natural Language Processing
 
	• Text Processing
	
   		○ Stopwords, Tokenization, Lemmatization
		
  		○ Bag of Words, TF-IDF
	
 	• Multi-class Classification
**What does ‘good’ look like?**
		
	  • Installing & Importing all the required libraries and Loading the dataset.
	
	  • Conduct a preliminary analysis to understand the structure of the dataset and the distribution of news articles in each category.
	
	  • Create a user defined function to process the textual data (news articles).
	
		   ○ Remove non-letters
		
		   ○ Remove Stopwords
		
		   ○ Word Tokenize the text
		
		   ○ Perform Lemmatization
		
	  • Display how a single news article looks like before and after the processing.
	
	  • Encode the target variable (category) using Label/Ordinal encoder.
	
	  • Create an option for the user to choose between Bag of Words and TF-IDF techniques for vectorizing the data.
	
	  • Perform train-test split and train a Naive Bayes classifier model using the simple/classical approach.
	
	  • Evaluate the model’s performance and plot the Confusion Matrix as well as Classification Report.
	
	  • Functionalize the code and train & evaluate three more classifier models (Decision Tree, Nearest Neighbors, Random Forest).
	
	  • Observe and comment on the performances of all the models used.

