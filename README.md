# ChatBot

Build a Chatbot Using Python, Django

![Demo](https://user-images.githubusercontent.com/66206865/202419615-cf68408c-4a21-4930-bb73-bd00c455d497.png)

## Technologies Used
- ChatterBot Library - To generate automated responses to a user’s input.
- Celery - Getting the automated response from a machine-learning dialog engine is going to take a while. So Celery will be used to perform this task in the background.
- WebSockets using Django Channels - To send to the client the automated response generated by the machine learning model immediately when it’s available.
- Redis - Will be used as a message broker and result backend for Celery. In addition, it will be used as a channel layer for WebSocket communication.
- TailwindCSS - To create the user interface.
