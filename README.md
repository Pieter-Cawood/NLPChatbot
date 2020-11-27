# NLPChatbot
This Jupyter Notebook implements a Seq2Seq (Keras module) + GloVe embeddings + Attention chatbot, interfaced with Telegram.
Trained using the transcripts of 617 movies.
<br><br>
![Chatbot](/resources/logo2.png )

## Installation
1. Create a 'data' and 'glove' folder in the project root.
2. Get the movie-dialogs https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html
- Place 'movie_conversations' and 'movie_lines' in the data folder.
3. Get the glove.6B,100 embeddings https://www.kaggle.com/danielwillgeorge/glove6b100dtxt
- Place glove.6B.100d.txt in the glove folder.
4. Check requirements.txt for Python package requirements.

## Acknowledgement
Thushan Ganegedara for sharing his Keras Attention layer. https://github.com/thushv89/attention_keras
