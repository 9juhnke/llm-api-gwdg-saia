# Examples for Using Large Language Models (LLMs) with the GWDG SAIA API

[SAIA](https://docs.hpc.gwdg.de/services/saia/index.html) is the Scalable Artificial Intelligence (AI) Accelerator that hosts AI services provided by the [GWDG](https://gwdg.de), including Large Language Models.

You need an [Academic Cloud ID](https://academiccloud.de/help/) to use it. **Students, researchers, and employees of registered universities with a valid university account** are eligible for an Academic Cloud ID.

Then you can request a [SAIA API (application programming interface) Key](https://docs.hpc.gwdg.de/services/saia/index.html#api-request) and use it to access the services from within your code.

## Description

The Repository contains easily understandable Jupyter Notebooks that show how to access features of the Large Language Models via the SAIA API. The API is [OpenAI-compatible](https://platform.openai.com/docs/api-reference/).

Currently, the following templates are available:

1. [Minimal Example](./minimal_example.ipynb) – demonstrates how to use the API in general
2. [Chat Completions](./chat_completions.ipynb) – so your app can chat
3. [Model List](./model_list.ipynb) – shows which models you can use via the API and what I/O they support
4. [Images](./images.ipynb) – get textual descriptions of images, e.g., for further interaction
5. [Embeddings / RAG](./embeddings_rag.ipynb) – example of how to set up a Retrieval Augmented Generation model
6. [Document Processing](./document_processing.ipynb) – extract text and images from PDFs
7. [Structured Outputs](./structured_output.ipynb) – build structured outputs from choices, with regex-patterns or as JSON (Yess!)

## Requirements

To run the examples, you need the following:
- a valid SAIA API key (from GWDG)
- Internet access to the SAIA API endpoint
- a Jupyter environment (e.g., JupyterLab or Google Colab)

## Installation

Install the required Python packages in your environment:
```bash
pip install openai
```

## Usage

Open the Jupyter Notebooks in your environment, **insert your API Key** and run it. Each notebook contains a self-contained, working example.

## Support

For questions or issues, please use the issue tracker or refer to the official SAIA documentation:

https://docs.hpc.gwdg.de/services/saia

For advanced features, as Structured Outputs in this example, see the vLLM documentation:

https://docs.vllm.ai/en/latest/features/structured_outputs.html

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository
1. Create a feature branch
1. Submit a merge request via Git

Feel free to open an issue if you want to discuss ideas first.
