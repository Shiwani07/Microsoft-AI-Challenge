# Microsoft-AI-Challenge
Given a user query and candidate passages corresponding to each, the task was to mark the most relevant passage which contains the answer to the user query. In the data, there were 10 passages for each query out of which only one passage is correct and the goal was to score the passages such that the actual correct passage gets as high score as possible.


Used Elmo embeddings to map the text data into vectors of real numbers. Bidirectional LSTM was trained using these word representations.

