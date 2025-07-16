# 🤖 LLM Python Notebook

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/simonpierreboucher02/llm_python_notebook-main/graphs/commit-activity)
[![GitHub stars](https://img.shields.io/github/stars/simonpierreboucher02/llm_python_notebook-main.svg)](https://github.com/simonpierreboucher02/llm_python_notebook-main/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/simonpierreboucher02/llm_python_notebook-main.svg)](https://github.com/simonpierreboucher02/llm_python_notebook-main/network)
[![GitHub issues](https://img.shields.io/github/issues/simonpierreboucher02/llm_python_notebook-main.svg)](https://github.com/simonpierreboucher02/llm_python_notebook-main/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/simonpierreboucher02/llm_python_notebook-main.svg)](https://github.com/simonpierreboucher02/llm_python_notebook-main/pulls)

[![Anthropic](https://img.shields.io/badge/Anthropic-Claude-blue.svg)](https://www.anthropic.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT-orange.svg)](https://openai.com/)
[![Cohere](https://img.shields.io/badge/Cohere-Command-purple.svg)](https://cohere.ai/)
[![Mistral](https://img.shields.io/badge/Mistral-AI-red.svg)](https://mistral.ai/)

---

<div align="center">

**A comprehensive collection of Jupyter notebooks for interacting with leading Large Language Model APIs**

[![Author](https://img.shields.io/badge/Author-Simon%20Pierre%20Boucher-blue.svg)](https://github.com/simonpierreboucher02)
[![GitHub Profile](https://img.shields.io/badge/GitHub-Profile-black.svg)](https://github.com/simonpierreboucher02)

</div>

---

## 📋 Table of Contents

- [Overview](#overview)
- [🚀 Features](#-features)
- [📁 Repository Structure](#-repository-structure)
- [🛠️ Getting Started](#️-getting-started)
- [📊 API Coverage](#-api-coverage)
- [💡 Use Cases](#-use-cases)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

## Overview

This repository contains **production-ready Jupyter notebooks** for accessing and interacting with various Large Language Model (LLM) APIs using Python. The notebooks provide a straightforward approach to setting up API calls and working with different LLM providers, including **Anthropic**, **Cohere**, **Mistral**, and **OpenAI**.

[![Repository Size](https://img.shields.io/github/repo-size/simonpierreboucher02/llm_python_notebook-main.svg)](https://github.com/simonpierreboucher02/llm_python_notebook-main)
[![Code Lines](https://img.shields.io/tokei/lines/github/simonpierreboucher02/llm_python_notebook-main.svg)](https://github.com/simonpierreboucher02/llm_python_notebook-main)
[![Last Commit](https://img.shields.io/github/last-commit/simonpierreboucher02/llm_python_notebook-main.svg)](https://github.com/simonpierreboucher02/llm_python_notebook-main)

## 🚀 Features

- ✅ **Multi-API Support**: Comprehensive notebooks for 4 major LLM providers
- ✅ **Ready-to-Run**: Complete setup instructions and examples
- ✅ **Production Ready**: Error handling and best practices included
- ✅ **Well Documented**: Detailed comments and explanations
- ✅ **Environment Management**: Proper dependency management with `requirements.txt`

## 📁 Repository Structure

| Notebook | Description | Status |
|----------|-------------|--------|
| **[PYTHON_ANTHROPIC_API.ipynb](PYTHON_ANTHROPIC_API.ipynb)** | Anthropic's Claude API integration with advanced prompting techniques | ![Anthropic](https://img.shields.io/badge/Status-Active-brightgreen.svg) |
| **[PYTHON_COHERE_API.ipynb](PYTHON_COHERE_API.ipynb)** | Cohere API setup with text generation and retrieval examples | ![Cohere](https://img.shields.io/badge/Status-Active-brightgreen.svg) |
| **[PYTHON_MISTRAL_API.ipynb](PYTHON_MISTRAL_API.ipynb)** | Mistral AI API configuration and parameter optimization | ![Mistral](https://img.shields.io/badge/Status-Active-brightgreen.svg) |
| **[PYTHON_OPENAI_API.ipynb](PYTHON_OPENAI_API.ipynb)** | OpenAI GPT models with comprehensive parameter tuning | ![OpenAI](https://img.shields.io/badge/Status-Active-brightgreen.svg) |

## 🛠️ Getting Started

### Prerequisites

[![Python Version](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Required-orange.svg)](https://jupyter.org/)

To run these notebooks, you need:
- **Python 3.8+**
- **Jupyter Notebook**
- API keys for each respective service (Anthropic, Cohere, Mistral, OpenAI)
- Required dependencies as listed in `requirements.txt`

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/simonpierreboucher02/llm_python_notebook-main.git
   cd llm_python_notebook-main
   ```

2. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your API keys**:
   Create a `.env` file in the root directory with your API keys:
   ```env
   ANTHROPIC_API_KEY=your_anthropic_key_here
   OPENAI_API_KEY=your_openai_key_here
   COHERE_API_KEY=your_cohere_key_here
   MISTRAL_API_KEY=your_mistral_key_here
   ```

### Running the Notebooks

1. **Start Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

2. **Select a Notebook**: Open the notebook for your desired API provider
3. **Follow Instructions**: Each notebook includes specific setup and usage instructions

## 📊 API Coverage

| Provider | Models Supported | Features | Status |
|----------|------------------|----------|--------|
| **Anthropic** | Claude-3, Claude-2 | Text generation, conversation, safety controls | ✅ Active |
| **OpenAI** | GPT-4, GPT-3.5-turbo | Chat completion, function calling, fine-tuning | ✅ Active |
| **Cohere** | Command, Command-R | Text generation, embeddings, reranking | ✅ Active |
| **Mistral** | Mistral-7B, Mixtral | Text generation, chat completion | ✅ Active |

## 💡 Use Cases

- **🔍 API Interactions**: Comprehensive examples of API calls for text generation, retrieval, and other LLM tasks
- **⚙️ Parameter Configuration**: Customize temperature, token limits, and prompt styles for optimal results
- **🔄 Multi-Model Comparisons**: Test and compare different LLM providers for various NLP applications
- **🚀 Production Integration**: Ready-to-use code snippets for production environments
- **📚 Learning Resource**: Educational material for understanding LLM API interactions

## 🤝 Contributing

[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg)](https://github.com/simonpierreboucher02/llm_python_notebook-main/pulls)

We welcome contributions! Feel free to:

- 🐛 **Report bugs** by opening an issue
- 💡 **Suggest new features** or improvements
- 📝 **Submit pull requests** to enhance functionality
- 📚 **Improve documentation** and examples

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Made with ❤️ by [Simon Pierre Boucher](https://github.com/simonpierreboucher02)**

[![GitHub](https://img.shields.io/badge/GitHub-Profile-black.svg)](https://github.com/simonpierreboucher02)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue.svg)](https://linkedin.com/in/simonpierreboucher02)

*If this repository helps you, please give it a ⭐ star!*

</div>

