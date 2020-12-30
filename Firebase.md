**Firestore**
- It store everything in form of documents and collections.
  - *Documents:* Contain the data in form of key value pair of every type like string, json, binary etc.
  - *Collections:* Contain the collection of documents.

  **Rules:**
  1. Collection can only contain documents, no other form of data like string.
  2. Documents can contain other documents but can't point to sub collections.
  3. Root of the database can only contain collections, means at root of any created db you can't insert documents.