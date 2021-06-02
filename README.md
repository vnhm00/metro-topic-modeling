The project is supervised by Aarne Klemetti and Janne Kauttonen.
<br/>

## 26 May &nbsp;—————————————
Completed:
- Explored the new dataset, did a little cleaning
- Tested models with new dataset
- Continued thesis writing: checked old codes, found lots of errors, and room to improve the old data analysis process

Plan for next week:
- Run the new dataset using LDA model, after that run with DTM
- Write thesis when possible

## 19 May &nbsp;—————————————
Completed:
- Experimented Puhti, run the first tests
- Fixed errors, warnings in Puhti (mostly it was because of libraries's old versions)
- Fixed read pickle file error (because older version of Python in Puhti)

Plan for next week:
- Work with new data from Janne
- Run models with the new dataset
- Continue thesis process

## 12 May &nbsp;—————————————
Completed:
- Added coherence scores for Dynamic Topic Models
- Finalized code for Janne to run in Puhti
- Started thesis writing process

Plan for next week:
- Experiment with Puhti
- Double-check the dataset (missing 2019, 2020 theses)
- Implement pickle dataset

## 06 May &nbsp;—————————————
Completed:
- Included different coherence scores: c_v, c_uci and c_npmi
- Added 'date' into the datasets, divided time slices for LDA sequence models
- Run Dynamic Topic Models with interval of 2 years
- Created Github repository, update files

Plan for next week:
- Start the thesis
- Add the coherence scores for Dynamic Topic Models
- Send code + dataset to Janne

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
