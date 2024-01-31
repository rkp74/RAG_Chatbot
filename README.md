Project Overview
This project aims to demonstrate a comprehensive pipeline for extracting information from Wikipedia texts using advanced language models and conversational systems. The workflow includes:

1. Data Collection :- 
We start by downloading 20 Wikipedia texts, comprising 15 related texts on a specific topic and 5 randomly selected texts on unrelated topics. The related texts are chosen to cover various aspects of a theme, creating a coherent set.

2. Text Embedding Generation :- 
Next, embeddings for each text are generated using BERT or a similar language model. Hugging Face Transformers library is employed for this task. This step provides a rich representation of the semantic content of the documents.

3. Question Answering with Langchain :- 
Langchain, a Python library, is utilized for question-answering on the documents. The official documentation here guides us through the process of setting up a question-answering system.

4. Enhancing Accuracy with Embeddings :- 
The embeddings generated in the previous step are leveraged to enhance the accuracy of the question-answering system. By incorporating these embeddings, we aim to improve the system's understanding of the document content.

5. Conversation Creation with Prompt Chaining :- 
Langchain is again employed to create a conversation using prompt chaining. Refer to the official documentation for guidance on creating interactive and natural conversations.

6. Interactive User Interface :- 
The prompts in the conversation are designed to allow for follow-up questions, creating a more natural and engaging interaction. This design encourages users to explore diverse topics within the context of the original documents.

7. Deliverables :- 
The project includes a Python notebook or script that automates the entire process. Detailed documentation accompanies each step, providing insights into the methodology, design decisions, and implementation details.
