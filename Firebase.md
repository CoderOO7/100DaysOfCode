## Firestore 

It's a nosql realtime database. It oraganzie and store data in form of documents and collections.

  - **Documents:** These are the Object's like a javscript object that contain the data in form of key value pair of every type like string, json, binary or blob etc.

  - **Collections:* These are the group of documents.


**Rules:**

1. Collection can only contain documents, no other form of data like string.
2. Documents cannot contain other documents but can point to sub collections.
3. Root of the database can only contain collections, means at root of any created db you can't insert documents.