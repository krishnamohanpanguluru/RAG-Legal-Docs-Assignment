# RAG-Legal-Docs-Assignment

# overview :-
In this case study, we will explore the fundamental components of a Retrieval-Augmented Generation (RAG) system using a corpus of textual data.
Implementing the key stages of a basic RAG pipeline, including document loading, creating an embedding layer, using a vector database for storing embeddings, and the integration of retrieval with language generation models. 
Along with this,  utilise Gen AI Frameworks like LangChain or LlamaIndex. These frameworks provide developers with the necessary tools and abstractions that reduce the development time for building AI applications as well as developing LLM-agnostic applications. The aim is to develop practical skills in combining structured retrieval techniques with unstructured language generation to support intelligent information access.



# Business Objective :-

The main objective of this assignment is to process and analyse a collection text files containing legal agreements (e.g., NDAs) to prepare them for implementing a Retrieval-Augmented Generation (RAG) system. This involves:

- Understand the Cleaned Data : Gain a comprehensive understanding of the structure, content, and context of the cleaned dataset.
- Perform Exploratory Analysis : Conduct bivariate and multivariate analyses to uncover relationships and trends within the cleaned data.
- Create Visualisations : Develop meaningful visualisations to support the analysis and make findings interpretable.
- Derive Insights and Conclusions : Extract valuable insights from the cleaned data and provide clear, actionable conclusions.
- Document the Process : Provide a detailed description of the data, its attributes, and the steps taken during the analysis for reproducibility and clarity.
The ultimate goal is to transform the raw text data into a clean, structured, and analysable format that can be effectively used to build and train a RAG system for tasks like information retrieval, question-answering, and knowledge extraction related to legal agreements.

# Data Understanding :-
The dataset contains legal documents and contracts collected from various sources. The data includes a variety of legal documents such as privacy policies, merger agreements, and non-disclosure agreements. Using these, we can build upon a base of precedents and domain knowledge.

The documents are present as text files (.txt) in the corpus folder. There are four types of documents in the corpus folder, divided into four subfolders.

- contractnli: contains various non-disclosure and confidentiality agreements
- cuad: contains contracts with annotated legal clauses
- maud: contains various merger/acquisition contracts and agreements
- privacy_qa: a question-answering dataset containing privacy policies

The dataset also contains evaluation files in JSON format in the benchmark folder. The files contain the questions and their correct answers, along with sources. For each of the above four folders, there is a JSON file: contractnli.json, cuad.json, maud.json, privacy_qa.json.


Legal firms and departments often handle large volumes of complex documents, making it difficult to efficiently find specific information. A streamlined RAG-based solution provides quicker and more precise responses to legal queries by dynamically retrieving and contextualising relevant excerpts from a legal corpus.

By adopting this approach, legal professionals can save time on document review, enhance research accuracy, and make more informed decisions. By adopting this approach, legal professionals can save time on document review, enhance research accuracy, and make more informed decisions.
