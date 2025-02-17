# Objective
- Developer Opportunity at Cisco through Del Oro Coosulting
Design and implement a Python class that provides an interface for CRUD operations on text documents within a vector database.

## Task
Your challenge is to create a Python class that encapsulates the interaction with a vector database of your choice (such as Weaviate, FAISS, ChromaDB, etc.). The class should enable the following operations:
- Collection Creation: Define a method that creates a new collection or index within the vector database to store vectorized text documents.
- Document Insertion: Implement a method that receives a plain text input, vectorizes it, and adds it as a new entry in the collection.
- Document Update: Develop a method that updates or replaces an existing text entry in the database with new text provided as an argument.
- Document Deletion: Create a method that deletes a text entry from the database based on a specified identifier.
- Document Retrieval: Create a method that receives a plain text input and a number N. Return the top N documents from the database that are ordered in relevancy to the text.


## Getting Started

To set up and run the on your local machine, follow the steps below:

### Prerequisites

- Python 3.11

### Installation

1. Clone the repository to your local machine and Change Directory:

```
git clone https://github.com/wilberh/vector_base_document
cd vector_base_document
```
2. Create Virtual Env and Install Requirements:

```
python -m venv env
env\Scripts\activate  # On Windows
source env/bin/activate  # On macOS/Linux
pip install -r requirements.txt
```

### Testing

1. **Using Pytest:**

   Run the following command to run test-cases:

   ```
   pytest ...
   ```

2. **Other Python Packages and APIs:**

   This project leverages this Python packages and external APIs,
   - ...
   - ...
   
## Bugs and Feature Requests
Have a bug or a feature request? Please open an [issue](https://github.com/wilberh/vector_base_document/issues/new).

## License
This project is [MIT](https://github.com/wilberh/vector_base_document/blob/main/LICENSE) licensed.

## Feedback
For feedback or any inquiries, feel free to contact and connect with me on LinkedIn:
[LinkedIn](https://www.linkedin.com/in/wilberhdez26/)

