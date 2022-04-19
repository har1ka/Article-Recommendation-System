## Article-Recommendation-System
There  are  instances  where  people  are  looking  for  articles  or  documents  that  are  quite  related  to  each other. In other words, they are trying to explore documents that have content that is similar to the already read  articles  or  in  other  words,  articles  that  are  close  to  their  interests.  By  leveraging  unsupervised learning, it is possible to extract the insights from articles and provide new results to the reader based on their similarity.  

### Problem Statement 
Our  goal  is  to  provide  the  articles  that  are  semantically  and  structurally  similar  to  the  already  read articles. Our motivation behind choosing this recommender system is our personal interest for reading including the academia related.  

### Data Source 
Our dataset  consists of  ~3,000 public articles shared on CI&T’s communication platform. Articles  are  in  different  formats  including  HTML  and  Video.  There  are  two  files  namely “shared_articles.csv” and “users_interactions.csv”. Each of these files describe in a detailed manner how the articles and readers are related which could be used to extract valuable insights. There are a lot of useful features for content based filtering and collaborative filtering. Features such as userCountry (Country of the user) and the userAgent (Web browser) are typically some useful features that could be considered for filtering content to the users and recommending them articles. Furthermore, the most important feature is ‘text’ which helps us identify frequent words and recommend based on the similarity scores with other articles.  

### Process
For clustering based recommender system, two features - text and title are important. 


