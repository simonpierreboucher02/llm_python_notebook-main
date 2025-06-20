# LLM Python Notebook

This repository contains Jupyter notebooks for accessing and interacting with various Large Language Model (LLM) APIs using Python. The notebooks provide a straightforward approach to setting up API calls and working with different LLM providers, including Anthropic, Cohere, Mistral, and OpenAI.

## Repository Structure

- **[PYTHON_ANTHROPIC_API.ipynb](https://github.com/simonpierreboucher/llm_python_notebook/blob/main/PYTHON_ANTHROPIC_API.ipynb)**: A notebook demonstrating the use of Anthropic's API for making requests, handling responses, and configuring parameters for different tasks.
- **[PYTHON_COHERE_API.ipynb](https://github.com/simonpierreboucher/llm_python_notebook/blob/main/PYTHON_COHERE_API.ipynb)**: Contains setup and usage instructions for the Cohere API, with examples for text generation and retrieval tasks.
- **[PYTHON_MISTRAL_API.ipynb](https://github.com/simonpierreboucher/llm_python_notebook/blob/main/PYTHON_MISTRAL_API.ipynb)**: Shows how to interact with the Mistral API, including configuration of model parameters and API responses.
- **[PYTHON_OPENAI_API.ipynb](https://github.com/simonpierreboucher/llm_python_notebook/blob/main/PYTHON_OPENAI_API.ipynb)**: Provides an introduction to the OpenAI API, covering setup, API calls, and adjusting parameters for optimal results.

## Getting Started

### Prerequisites

To run these notebooks, you need:
- **Python 3.8+**
- **Jupyter Notebook**
- API keys for each respective service (Anthropic, Cohere, Mistral, OpenAI)
- Required dependencies as listed in `requirements.txt`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/simonpierreboucher/llm_python_notebook.git
   cd llm_python_notebook
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebooks

1. **Start Jupyter Notebook**: Open Jupyter by navigating to the repository folder and running:
   ```bash
   jupyter notebook
   ```
2. **Select a Notebook**: Open the notebook for the desired API provider (Anthropic, Cohere, Mistral, or OpenAI).
3. **Follow Instructions**: Each notebook includes specific instructions for authenticating, setting up, and making API requests to interact with the respective LLMs.

## Use Cases

- **API Interactions**: Each notebook provides examples of API calls for text generation, retrieval, and other common LLM tasks.
- **Parameter Configuration**: Customize parameters such as temperature, token limits, and prompt styles to achieve desired model behavior.
- **Multi-Model Comparisons**: Enables testing and comparing different LLM providers for various applications in NLP.

## Contributing

We welcome contributions! Feel free to submit issues or pull requests to enhance functionality, add features, or address any bugs.

## License

This repository is licensed under the MIT License.

