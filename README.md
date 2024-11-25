## End - to - End Multi AI RAG Agent Using LangGraph
* Inside this project, I have built a multi AI agent with RAG using LangGraph and AstraDB with integration with the Llama 3.1 open source model using Groq API key
* In this we use a Vector store database which is our AstraDB and store some documents using a web based loader in the form of vectors.
* We also use an external tool which is wikipedia search (wiki search). You can also add more tools if you like.
* So, whenever the user gives a query it first goes through a router, whose job is to route the query to wiki search or vectorstore database based on the query and who can give the answer.

## Setup
* Built and run entirely in Google Colab.
