# Agentic HR Document Search Assistant

A Jupyter Notebook–based agentic tool for searching and retrieving information from HR policy and procedure documents using a language model agent.

## Description

The project outlines how to build an agentic document search assistant in Python. The assistant can answer queries over a collection of HR documents (policies, procedures, handbooks, etc.) by making use of a large language model. The implementation is provided in a single notebook for ease of exploration and customization.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/agentic-hr-search.git
   cd agentic-hr-search
   ```
2. (Optional) Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate        # On Windows: venv\Scripts\activate
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Main.ipynb
   ```
2. In the notebook:
   - Load and preprocess your HR documents.
   - Configure your API key or local model endpoint.
   - Run the agent cells to issue queries and receive answers.
3. To extend functionality:
   - Modify prompts.
   - Add or remove documents.
   - Switch model backends.

