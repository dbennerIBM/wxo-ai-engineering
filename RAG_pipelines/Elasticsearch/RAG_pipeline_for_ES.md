# Building better RAG agents with Docling Granite 4, Granite embedding models, and Elasticsearch 
## This guide specifically covers Enterprise and Platinum versions of Elasticsearch on IBM Cloud and IBM TechZone which both use ES version 8.x and typically 8.15

Here are some links to learn more about Granite Docling multimodal image-text-to-text model for efficient document conversion:
- 💻 [granite docling 258 on hugging face](https://huggingface.co/ibm-granite/granite-docling-258M)
- 🍎 [granite docling 258M mlx on hugging face](https://huggingface.co/ibm-granite/granite-docling-258M-mlx) **Apple Silicon** Mac optimized with mlx
- 🚀 [Docling Github](https://github.com/docling-project/docling/blob/main/README.md)
- 📚 [Docling project documentation](https://docling-project.github.io/docling/)
- 🤓 [IBM Granite community - Docling workshop](https://ibm-granite-community.github.io/docling-workshop/)

Here are some links to learn more about Elasticsearch's PoV on RAG:
- [Chunking strategies for elasticsearch](https://www.elastic.co/search-labs/blog/chunking-strategies-elasticsearch)


The intent of the RAG_pipeline_docling_granite_elasticsearch.ipynb is to provide a complete RAG pipeline for Elasticsearch vector databases. A key focus is to see how to simple it is to implement Granite Docling in a RAG pipeline.  