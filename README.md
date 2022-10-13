# NLP-project-Mental-Graph-Of-Users-Using-Social-Media-Posts-
Mental Graph Of Users Using Social Media Posts - g2

# Methodology
Extracting Twitter Tweets & Youtube Comments from videos.<br>
Classifying positive and negative sentiments from extracted data.<br>
Among the negative sentiments classifying them further into hate and criticism posts.<br>
Plotting a bar graph of different negative sentiment from a user.<br>

# Steps Of Project
Data Extraction & Labelling <br>
Data Preprocessing <br>
Data Visualization <br>
Word Embeddings <br>
Models <br>
Results <br>
Model Deployment <br>

# Data Extraction & Labelling
### Extraction:
Made use of snscrape library and Youtube API for extracting Twitter and YouTube data respectively. <br>

### Labelling:
Performed manual labelling for first classification into 2 classes i.e Positive , Negative. <br>
Further performed manual labelling for second classification into 2 classes i.e. Hate and Criticism .<br>

# Data Preprocessing
Removed Urls from tweets   <br>
Removed hashtags and emoticons <br>
Removed special characters <br>
Removed Retweet markers <br>
Removed Stopwords <br>
Applied Lemmatization <br>

## Word Embeddings
Used word2vec word embeddings. <br>
Embedding Dimension: 200 . <br>
Vocab Size: 1600 . <br>
![image](https://user-images.githubusercontent.com/58140667/195680150-1f33e6c3-5459-4295-be43-bd9d3931d5dc.png)
![image](https://user-images.githubusercontent.com/58140667/195680188-abf64dae-1a84-485e-a6b0-8caac6c55522.png)

# Models Implemented
Two models applied one for sentiment analysis and other for hate and criticism classification <br>
1. Bidirectional LSTM <br>
2. Small Bert <br>

# Future Scope
1. Making use of huge data. <br>
2. Adding more project specific cleaning steps. <br> 
3. Adding hindi language to the model. <br>
4. Finding better word embedding algorithm. <br>
5. Finding better classification model. <br>
6. Developing more interactive user interface. <br>
7. In short, to make a project complex enough to actually help the officials to track down targeted people.  


