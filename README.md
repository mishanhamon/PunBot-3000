
# PunBot-3000
PunBot 3000 is a retrieval-based chatbot that creates puns on a specified topic and is integrated with Telegram.  

This chat bot was created as a capstone project for the "Build Chatbots with Python" skillpath at Codecademy (Codecademy user name: @mishanhamon). The PunBot.ipynb file contains the main elements of the chatbot, while the user-functions.py contains additional functions. note that you would need a telegram chat bot token to use the script. 

The project uses homophone sourcing technique developed by Kamran Janjua (2020, available at https://github.com/kjanjua26/Pyphones/tree/master) and a dataset of English idioms created by zaghloul404 (2023, available at https://github.com/zaghloul404/englishidioms/tree/main) under the open license. 

# About the project

The aim of this project was to create a chatbot that would be able to generate a pun on a topic, specified by the user. This is why it is based on a closed-domain architecture and can't do much else aside from puns. While the initial idea was to develop a generative chatbot, a retrieval-based solution was chosen due to the lack of data on puns.

PunBot 3000 exploits three linguistic elements of puns. First, every pun by PunBot 3000 is structured as a question and an answer. Second, for a given topic, the chatbot attempts to find a relevant idiom and integrate it into the answer. Third, the chatbot attempts to replace the topic in the identified idiom with a homophone to create a silly wordplay. 

PunBot 3000 is created for purely entertainment purposes but might be useful for the research of humour. My beta-tester - my wife - said that while some puns were not making much sense, she found other jokes "quite funny" and was overall satisfied with the experience. 

The chatbot relies on machine learning (ML) and natural language processing (NLP) techniques. For every user message, it uses ML entity recognition to identify the word that is most likely to be the topic of the desired pun. It also employs ML intent classification to select the response that has the highest similarity with the user's message. To operate these processes, PunBot 3000 uses the word2vec NLP technique. 

# Example of usage via Telegram

https://github.com/mishanhamon/PunBot-3000/assets/167139491/b5ee8375-c3d3-41c2-9ea3-b4719bd99349
