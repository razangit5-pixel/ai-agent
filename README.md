# AI Agent

A collection of Jupyter notebooks from my hands-on learning of AI agents. The notebooks walk through the basics of building agents, starting with instantiating a prebuilt agent.

## Contents

| Notebook | Description |
|----------|-------------|
| `lesson_!.ipynb` | Introductory lesson notebook |
| `2_1_instantiate_prebuilt_agent_try_it.ipynb` | Hands-on exercise: instantiating and running a prebuilt agent |

## Getting Started

### Prerequisites

- Python 3.10 or newer
- Jupyter Notebook or JupyterLab
- An API key for your LLM provider (if the notebooks call a hosted model)

### Installation

```bash
git clone https://github.com/razangit5-pixel/ai-agent.git
cd ai-agent
python -m venv .venv
source .venv/bin/activate    # Windows (Git Bash): source .venv/Scripts/activate
pip install jupyter
```

Install any additional packages the notebooks import (for example your agent framework of choice).

### Configuration

Store secrets such as API keys in environment variables or a `.env` file. Never commit them to the repository.

```bash
export API_KEY="your-key-here"
```

### Running the notebooks

```bash
jupyter notebook
```

Open a notebook from the file browser and run the cells in order.

## Project Structure

```
ai-agent/
├── lesson_!.ipynb
├── 2_1_instantiate_prebuilt_agent_try_it.ipynb
└── README.md
```

## Roadmap

- [ ] Add more lesson notebooks
- [ ] Add a `requirements.txt`
- [ ] Add examples of custom tools for agents

## Author

Razan — [@razangit5-pixel](https://github.com/razangit5-pixel)
