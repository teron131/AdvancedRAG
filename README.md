# Advanced RAG

## References

### Advanced RAG Eval

https://github.com/langchain-ai/langchain/blob/master/cookbook/advanced_rag_eval.ipynb

### Semi-structured RAG

https://github.com/langchain-ai/langchain/blob/master/cookbook/Semi_Structured_RAG.ipynb

### Semi-structured and Multi-modal RAG

https://github.com/langchain-ai/langchain/blob/master/cookbook/Semi_structured_and_multi_modal_RAG.ipynb

### Multimodal RAG using Langchain Expression Language And GPT4-Vision
https://medium.aiplanet.com/multimodal-rag-using-langchain-expression-language-and-gpt4-vision-8a94c8b02d21

### llama.cpp

https://github.com/ggerganov/llama.cpp

### ggml_llava-v1.5-7b

https://huggingface.co/mys/ggml_llava-v1.5-7b/tree/main

## Multi-Vector Retriever for RAG on Tables, Text, and Images

https://blog.langchain.dev/semi-structured-multi-modal-rag/

![Multi-Vector Retriever](multi-vector-retriever.png)

![Multimodel and Multi-Vector Retriever](multimodel-and-multi-vector-retriever.png)

This article discusses advancements in Retrieval Augmented Generation (RAG), focusing on seamless question-answering across diverse data types like images, text, and tables. It highlights the release of three new cookbooks demonstrating the use of a multi-vector retriever for RAG on documents containing mixed content types. These cookbooks also explore how multimodal Large Language Models (LLMs) can be paired with the multi-vector retriever to enhance RAG, particularly for images.

Key aspects include:

1. **Context and Improvement of RAG**: RAG combines the reasoning ability of LLMs with external data sources, enhancing factual recall. Techniques for improving RAG, like base case RAG, summary embedding, windowing, metadata filtering, fine-tuning RAG embeddings, and 2-stage RAG, are discussed.
2. **Multi-Vector Retriever**: The multi-vector retriever decouples documents used for answer synthesis from references used for retrieval. It's effective for raw text, tables, and images, aiding RAG.
3. **Document Loading and Semi-Structured Data**: The article describes how tools like Unstructured can extract different elements (tables, images, text) from files for processing. This is crucial for handling semi-structured data, where naive chunking strategies might split tables.
4. **Multi-Modal Data and Cookbooks**: The article presents three approaches for integrating images into RAG, utilizing multimodal embeddings, multimodal LLMs, and various combinations of text and image summaries. It also includes specific cookbooks for semi-structured RAG and multi-modal RAG, both public and private.
5. **Testing and Local Deployment**: The use of LLaVA, a multimodal LLM, for image summarization is tested, demonstrating its effectiveness in generating meaningful summaries. The article also notes that the RAG pipeline can be run locally on consumer laptops with open-source components.