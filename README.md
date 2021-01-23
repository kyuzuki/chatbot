# Lilo & Stitch Chatbot
Basic Python-implemented chatbot focused on Lilo &amp; Stitch, created for an assignment in CogSci 131: Computational Models of Cognition at UC Berkeley, Spring 2020.

This was a short project, and there are ways that I could improve the chatbot's performance. When there is a close match (or no match), the chatbot turns the user's question into another question back at the user. One way to improve its performance is to add the ability to conjugate verbs so that it can match something that is a close match. For example, "Reuben can make sandwiches" conveys the same information as "Ruben makes sandwiches", but the chatbot currently doesn't recognize them as the same since "make" and "makes" are different.


`hw4.ipynb` contains the code to implement the chatbot.`convo.ipynb` and `convo-1.ipynb` demonstrate me interacting with the chatbot, while `friend-convo.ipynb` includes my friend's interactions with the chatbot.
