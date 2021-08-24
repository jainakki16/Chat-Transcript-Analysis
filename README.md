<h1 align = 'center'> Students Performance in online classes </h1>

<h2><b>Problem Statement</b></h2> 

The covid-19 pandemic has affected the education system. Daily progress monitoring of student’s performance that was so prevalent in the offline method of teaching has been hampered due to the unavailability of class interaction and personal attention.
<br>

<h2><b>Objective</b></h2> 
Past year many schools and colleges have introduced online forums where teachers ask questions to check student’s attentiveness and performance. We used transcripts of forums to monitor and study the class participation of students in online lectures.
<br>

<h2><b>Important Points</b></h2>

• Data were collected from the college’s technical department in multiple `.txt files` which were then converted into flat files(likes TSV) and merged into a single dataset for analysis.<br>

• Dataset has three columns - `Timestamp of reply`, `Name of student`, and `content of the chat` but analyzing categorical data was challenging.<br>

• Data cleaning was a rigorous task where we fixed `misspelled words`, `abbreviations`, `removed picture characters` like emojis.<br>

• In `data exploration`, we used `data visualization` methods such as graphs, histograms, etc to analyze responses between the student’s across different sessions more simply and effectively. Libraries like NLTK were used to find stopwords, most commonly used words, etc.<br>

• Used `GloVe` which is a `pre-trained word embedding model`, to compare the similarity between the answer of students and the correct answers provided by the teacher at the end of the session.<br>

• Provided detailed analysis of the students’ performance like daily attendance, daily response, number of correct responses, number of questions asked by the teacher in each session, number of responses to each question, etc. in `Tableau`.<br><br>

<h2><b>Suggestions</b></h2>
From many [studies](https://jisajournal.springeropen.com/articles/10.1186/s13174-019-0120-0), we found that many students lack interest in these traditional chat-based forums due to the unavailability of modern aesthetics present in social media platforms. We have suggested our college add features like image upload, upvote options, and filters which may increase the enthusiasm of students to participate and attend classes.<br><br>
