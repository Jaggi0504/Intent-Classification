Intent Classification is important for several reasons:
1. Efficient communication
2. Improved user experience
3. Task automation and much more

In this project, I was given a task to classify three intents: 
1. Task create
2. Schedule update
3. Query

Given a user query/message, the task was to identify the intent of the message. 
To perform this task, I did the following:
1. Used OpenAI API key for embedding
2. Used PineconeAPI key and created an index.
3. Created almost 50 messages for each intent (task create, schedule update, and query) and then embedded them separately.
4. Upserted the three above created vectors into Pinecone along with the namespace to uniquely identify the index.
