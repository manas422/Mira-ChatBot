# Mira-ChatBot 
# Pandeyji Eatry Chatbot

Welcome to Pandeyji Eatry Chatbot! This project showcases a chatbot built using Google Dialogflow for the conversational AI and FastAPI for the backend. The chatbot assists users in placing food orders at Pandeyji Eatry, while utilizing a database named `pandeyji_eatry` to manage orders. Additionally, it uses ngrok to enable secure HTTPS communication for webhook integration.

## Features

- **Dialogflow Integration:** The chatbot leverages Google Dialogflow's natural language processing capabilities to engage in interactive conversations with users.

- **FastAPI Backend:** The backend of the chatbot is powered by FastAPI, a modern and efficient web framework, allowing seamless communication between the chatbot interface and the database.

- **Database Interaction:** The chatbot uses the `pandeyji_eatry` database to manage customer orders. Orders are stored and retrieved to ensure a smooth ordering experience.

- **ngrok for HTTPS:** ngrok is utilized to securely convert HTTP requests into HTTPS, ensuring data security and integrity during communication between the chatbot and external services.

## Prerequisites

- Google Dialogflow account and project setup.
- FastAPI installed in your environment.
- PostgreSQL database named `pandeyji_eatry`.
- ngrok installed for secure webhook integration.
