# Vector-Embeddings-Conversion-Using-Chroma-DB
Using Chroma DB Libraries to convert Document into vector embeddings

Prerequisites:
To follow this tutorial, you will need to have Python and Docker installed on your local machine.


What is Chroma DB?

Chroma DB is a vector database system that allows you to store, retrieve, and manage embeddings.
It can be used in Python or JavaScript with the chromadb library for local use, or connected to a remote server running Chroma. Users can configure Chroma to persist data on disk and create collections of embeddings using unique names.
The client object provides methods like `heartbeat()` and `reset()`.
To run Chroma in client/server mode, install the `chromadb` library and start the Chroma server with a given path.
The JS client then connects to the Chroma server backend.

First install chroma db in your notebook:
![image](https://github.com/user-attachments/assets/ae6caf92-7b5b-4a85-8f98-48d22ef46e01)

Then,import the chromadb library and create a new client object:
![image](https://github.com/user-attachments/assets/ec21eedd-91ca-482a-a5ff-d6858a9e360c)

Next, create a new collection with the create_collection() method:
![image](https://github.com/user-attachments/assets/c20c307d-36ee-4572-b9e5-a426a9e2a493)

Now, add some documents to the collection using the add() method:
![image](https://github.com/user-attachments/assets/d26b2678-4af1-458e-94f6-856b1d3282a9)

Finally, query the collection using the query() method:
![image](https://github.com/user-attachments/assets/2eb74b21-2f00-4e60-8743-1fb964e46751)


Output:
![image](https://github.com/user-attachments/assets/5313b570-f9f1-455a-94d5-d64424bb5a42)






