# Potential-Talents
## Data Science Project

The objective of the project was to automate the process of finding potential talented individuals for technology companies. 
We are also interested in developing a machine learning powered pipeline that could spot talented individuals and rank them based on their fit for a given role.

We generally make these searches based on some keywords based on the role we are trying to fill.

# Background and Problem Statement

A talent sourcing and management company is interested in finding talented individuals for sourcing these candidates to technology companies. Finding talented candidates is not easy, for several reasons. The first reason is one needs to understand what the role is very well to fill in that spot, this requires understanding the client’s needs and what they are looking for in a potential candidate. The second reason is one needs to understand what makes a candidate shine for the role we are in search for. Third, where to find talented individuals is another challenge.
To automate this process, we want to build a better approach that could save us time and finally help us spot potential candidates that could fit the roles we are in search for. 
Candidates will be matched based on how fit they are for the given role. Searches will be done using keyword based on the role that is being filled. Fit will be determined, and candidates ranked based on their fit.
For this problem we will us the keywords: “Aspiring human resources” or “seeking human resources”.
Project overview
The project was carried out using data from a talent sourcing management company. Potential candidates’ resumes are obtained, and keyword search carried out to determine the candidate with the best fit for the role.
The data consists of 104 rows and 5columns, with one column – fit with no values. This will be computed by the machine learning algorithm and populated for each candidate based on the keyword search.  Refer to the data dictionary for more details on the information given in each column. The dataset was cleaned and transformed using feature engineering where necessary.  
In this project python was used to build predictive models. NLP (Natural Language Processing) techniques were used to determine the fit of a candidate using the given keyword searches. TFiDF Vectorizer was combined with Cosine similarity to determine how fit a candidate is for a role. The fit was then used to rank the candidate for a specific role.

# Prerequisites

To run the code, there were a number of Python libraries that needed to be installed. These are as follows:

●	Pandas
●	NumPy
●	Matplotlib
●	Seaborn
●	Nltk corpus
●	Stopwords
●	WordNetlemitizer
●	WordCloud
●	Tfidfvectorizer
●	Cosine_similarity


# Summary/Findings
We have used the fit as the metric to evaluate the performance of the models. This is determined using the cosine similarity between the words in the job title and words used in the keyword search. 
Two key word searches were done for this project. The first was done using the keywords “Aspiring human resources”.  The results for this search revealed several candidates with the same fit score. In this case the highest fit score was 0.7594, seven candidates were scored with this fit score.
The second keyword search was done using the keywords “seeking human resources”. In this search the highest fit score was 0.7096, with only one candidate obtaining this score. 
