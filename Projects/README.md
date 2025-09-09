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
<img width="1470" height="841" alt="Screenshot 2025-09-09 at 20 52 54" src="https://github.com/user-attachments/assets/5e04d28c-49fa-4ee5-836e-e393ed8de422" />
<img width="1470" height="838" alt="Screenshot 2025-09-09 at 20 53 32" src="https://github.com/user-attachments/assets/74fe5652-755a-4e12-8c48-82c6c99219af" />
<img width="1470" height="840" alt="Screenshot 2025-09-09 at 20 53 54" src="https://github.com/user-attachments/assets/4d9e8347-9361-4027-a3e3-2a8001249a09" />
<img width="1470" height="652" alt="Screenshot 2025-09-09 at 20 54 30" src="https://github.com/user-attachments/assets/82b87bc2-572a-48e9-95a0-19c2b1a899f7" />
<img width="1470" height="658" alt="Screenshot 2025-09-09 at 20 55 01" src="https://github.com/user-attachments/assets/d46d8e8d-2502-4ef3-9e72-5a5f3f51f8ac" />
<img width="1470" height="839" alt="Screenshot 2025-09-09 at 20 58 46" src="https://github.com/user-attachments/assets/3b072b94-d97d-4a3c-97f5-8f3c1fe57f00" />
<img width="1470" height="841" alt="Screenshot 2025-09-09 at 20 59 07" src="https://github.com/user-attachments/assets/cf4440dd-36d2-4f17-a7b8-c7a27e0e54d2" />
<img width="1470" height="837" alt="Screenshot 2025-09-09 at 20 56 20" src="https://github.com/user-attachments/assets/828423f9-baf4-49dc-857a-19b114eb1199" />
<img width="1468" height="839" alt="Screenshot 2025-09-09 at 20 56 39" src="https://github.com/user-attachments/assets/c53bdbb4-789e-4a39-90ce-7ee66efcb26e" />
<img width="1470" height="836" alt="Screenshot 2025-09-09 at 20 57 48" src="https://github.com/user-attachments/assets/2109bb0a-0e5b-4f1c-8b7e-0352297f3ebd" />
<img width="1470" height="839" alt="Screenshot 2025-09-09 at 20 58 11" src="https://github.com/user-attachments/assets/da42d4fa-c638-406c-8661-ded895b7733f" />




