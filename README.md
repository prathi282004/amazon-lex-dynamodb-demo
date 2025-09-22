# amazon-lex-dynamodb-demo

## 📌 Project Title  
**Chatbot using AWS Lex & DynamoDB**  

## 📌 Project Description  
This project demonstrates a chatbot built with **Amazon Lex** and **Amazon DynamoDB** to retrieve and interact with **student details**.  

The chatbot works in the following way:  
- The user provides a **Student ID**.  
- The bot checks the **DynamoDB table** to see if the ID exists.  
  - ✅ If found, the bot proceeds to ask the **next relevant question** (such as name, department, year of study, etc.) and retrieves the answer from the database.  
  - ❌ If not found, the bot **asks for the Student ID again** until a valid one is provided.  
- Based on the user’s needs, the bot can continue answering follow-up questions related to the student profile.  

This project shows how **Lex handles the conversational flow** while **DynamoDB ensures reliable data storage and retrieval**, all without additional backend code.  

## 🏗️ Architecture Diagram  
flowchart LR
    A[User] --> B[Amazon Lex]
    B --> D[(Amazon DynamoDB)]


## 📸 Screenshots
Lex Console – Intent Definition
![image alt](https://github.com/prathi282004/amazon-lex-dynamodb-demo/blob/071b5cdf802253a6cdb3ac3ba39999cb79cf6f1b/amazon_lex.png)

DynamoDB Table View
![image alt](https://github.com/prathi282004/amazon-lex-dynamodb-demo/blob/071b5cdf802253a6cdb3ac3ba39999cb79cf6f1b/dynamoDB.png)

Chatbot Conversation Demo (Test Console)
![image alt](https://github.com/prathi282004/amazon-lex-dynamodb-demo/blob/071b5cdf802253a6cdb3ac3ba39999cb79cf6f1b/sample_test_view.png)


## 🎯 Learning Outcomes
By completing this project, I gained practical experience with the following AWS skills:
- NLP Basics → Designing and training conversational interfaces using Amazon Lex.
- Data Storage → Using DynamoDB to manage and retrieve structured student records.
- Serverless Integration → Building solutions by directly integrating AWS services without backend servers.    
