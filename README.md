The project is supervised by Aarne Klemetti and Janne Kauttonen.
<br/>

## 28 April &nbsp;—————————————
Completed:
- Divide the datasets into smaller ones to plot the smoother coherence plots
- Added the bigrams and filtered common and rare words using *filter_extremes* (instead of TF-IDF)
- Included abbreviations in the dictionary
- Completed a good enough model that includes bigrams + abbreviations using 8 clusters (8 topics)

Plan for next week:
- Try to plot different coherence scores: c_v, c_uci and c_npmi
- Try to include 'date' and 'school' features into the datasets
- Apply Dynamic Topic Models with interval of 2 years
- Create Github repository, update files
- Remeber to update process with supervisors

## 21 April &nbsp;—————————————
Completed:
- Cleaned the texts more carefully: delete manually common words, delete rare words, etc.
- Tried only nouns datasets
- Ploted the topics using pyLDAvis
- Ploted the coherence line and tried different settings, different models

Plan for next week:
- Divide the datasets into smaller ones to plot the smoother coherence plots
- Try to obtain a better datasets by adding bigrams and TF-IDF to the data preprocessing
- Try to include 'date' and 'school' features into the datasets
- Extract abbreviations from abstracts
- Remeber to update process with supervisors

## 14 April &nbsp;—————————————
Completed:
- Submitted thesis form
- Read about Topic Modeling, TF-IDF, LSA, LDA models, etc.
- Implemented the very first LDA models

Plan for next week:
- Get to know the gensim library more
- Doing more experiments with different settings
- Divide the datasets into smaller ones to plot the smoother coherence plots

## 07 April &nbsp;—————————————
Completed:
- Extracted the abstracts, separating English and Finnish ones
- Preprocessed the texts: delete stop words, lemmatization (not successful with Finnish abstracts though due to installation error)
- Plotted (annually) word clouds for English and Finnish theses
- The process was longer than expected due to an error -> fixed by adding *collaboration = False* when creating the word clouds

Plan for next week:
- Submit the thesis form on Metropolia system
- Skip the Finnish dataset and work on the English ones first
- Get to know Topic Modeling
- Remeber to update process with supervisors

## 31 March &nbsp;—————————————
Completed:
- Joined the Virtual Hackathon
- Checked Janne's repo
- Started exploring the Theseus datasets: reading, briefly cleaning, categorize some features, plot some graphs

Plan for next week:
- Create (annually) word clouds for English and Finnish theses
- Remeber to update process with supervisors

## 24 March &nbsp;—————————————
Summary:
- Sign up for the Virtual Hackathon from Laurea UAS
- The project's goal is to handle abstracts data from Theseus, Aaltodoc, and Helda: scarping/extracting, gain valuable insights, build a NLP model
- Receive Janne's repo about scraping Theseus' theses
- Two paths to start with: continue scraping theses from Aaltodoc and Helda or experimenting on the Theseus dataset provided by Janne
