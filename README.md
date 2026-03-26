# LLM Engineering Special

A comprehensive learning project for understanding Large Language Model (LLM) engineering with OpenAI APIs and LangChain.

## Project Overview

This project is designed to provide hands-on experience with:
- OpenAI API integration and authentication
- LLM-based application development
- Vector databases and embeddings (ChromaDB)
- LangChain for building LLM chains and workflows
- Flask web framework integration
- Jupyter notebook-based learning modules

## Project Structure

```
ed-llm-engg/
├── main.py                 # Main entry point of the application
├── requirements.txt        # Project dependencies
├── pyproject.toml         # Project configuration and metadata
├── README.md              # This file
└── week1/
    └── day1.ipynb         # Week 1, Day 1: OpenAI API basics and authentication
```

## Requirements

- **Python**: >= 3.12
- **Dependencies**: See [requirements.txt](requirements.txt)

### Key Dependencies

| Package | Purpose |
|---------|---------|
| `openai` | Official OpenAI Python client |
| `langchain` | Framework for building LLM applications |
| `langchain-openai` | LangChain integration with OpenAI |
| `langchain-core` | Core LangChain abstractions |
| `langchain-community` | Community integrations for LangChain |
| `chromadb` | Vector database for embeddings |
| `flask` | Web framework for building APIs |
| `requests` | HTTP library for API calls |
| `python-dotenv` | Environment variable management |
| `ipykernel` | Jupyter notebook kernel |

## Installation

1. **Clone or download the project**
   ```bash
   cd ed-llm-engg
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

   Replace `your_openai_api_key_here` with your actual OpenAI API key from https://platform.openai.com/api-keys

## Usage

### Running the main application
```bash
python main.py
```

### Using Jupyter notebooks
```bash
jupyter notebook week1/day1.ipynb
```

## Learning Path

### Week 1
- **Day 1**: OpenAI API basics
  - Setting up OpenAI client authentication
  - Making basic API calls
  - Understanding chat messages format
  - Handling responses from GPT models

## Development

### Prerequisites
- Python 3.12 or higher
- OpenAI API key (sign up at https://platform.openai.com)

### Development Setup
1. Install dependencies: `pip install -r requirements.txt`
2. Configure your OpenAI API key in the `.env` file
3. Run notebooks or scripts to test functionality

## Notes

- Keep your OpenAI API key secure and never commit it to version control
- The `.env` file is excluded from version control (add to `.gitignore` if using Git)
- Each notebook in the `weekX/dayY.ipynb` format represents a learning module

## License

Add license information here if applicable.
