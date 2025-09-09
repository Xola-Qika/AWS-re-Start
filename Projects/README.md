# S3 Quiz Chatbot using Amazon Lex

## Objective
Create a text-based chatbot using Amazon Lex that ask users questions about Amazon Simple Storage Service

## Tasks
- Created a Lex Bot for text-only interaction and changed the language from English (US) to English (South Africa)
- Created an intent named S3Quiz and added four utterances named Hi, Begin quiz, Start quiz and Quiz me on S3 to start quiz
- Created two slot types, one was for the options that the user was going to choose and the other option was for the user to choose if they want to move to another question or not. 
- Add conditional branching. Checked if the answer is correct or not. Asked if the user wanted to continue after each question. Had a closing reponse if they said no.
- Deployed and test the bot. 

## Challenges
- Did nnot know I needed slot types. I kept on adding intial responses to my utterances and the quiz was not interacting. 
- When adding conditional branching I chose slot capture failure response and not slot capture success reponse. 

## Takeaways
- A single intent can manage complex quiz flows with proper slot and branching setup.
- Conditional branching creates dynamic, responsive conversations.

## Screenshots

