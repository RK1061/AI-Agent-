# AI-Agent-
**Project Setup Guide**

This guide provides step-by-step instructions to set up your project environment, including setting up a Python virtual environment using Pipenv, pip, or conda.

**Table of Contents**

1. [Setting Up a Python Virtual Environment](https://github.com/AIwithhassan/ai-agent-chatbot-with-fastapi/blob/main/Readme.md#setting-up-a-python-virtual-environment)
    - [Using Pipenv](https://github.com/AIwithhassan/ai-agent-chatbot-with-fastapi/blob/main/Readme.md#using-pipenv)
    - [Using pip and venv](https://github.com/AIwithhassan/ai-agent-chatbot-with-fastapi/blob/main/Readme.md#using-pip-and-venv)
    - [Using Conda](https://github.com/AIwithhassan/ai-agent-chatbot-with-fastapi/blob/main/Readme.md#using-conda)
2. [Running the application](https://github.com/AIwithhassan/ai-agent-chatbot-with-fastapi/blob/main/Readme.md#project-phases-and-python-commands)

**Setting Up a Python Virtual Environment**

**Using Pipenv**

1. **Install Pipenv (if not already installed):**

```
pip install pipenv

```

1. **Install Dependencies with Pipenv:**

```
pipenv install

```

1. **Activate the Virtual Environment:**

```
pipenv shell

```

---

**Using `pip` and `venv`**

**Create a Virtual Environment:**

```
python -m venv venv

```

**Activate the Virtual Environment:**

**macOS/Linux:**

```
source venv/bin/activate

```

**Windows:**

```
venv\Scripts\activate

```

**Install Dependencies:**

```
pip install -r requirements.txt

```

---

**Using Conda**

**Create a Conda Environment:**

```
conda create --name myenv python=3.11

```

**Activate the Conda Environment:**

```
conda activate myenv

```

**Install Dependencies:**

```
pip install -r requirements.txt

```

**Project Phases and Python Commands**

**Phase 1: Create AI Agent**

```
python ai_agent.py

```

**Phase 2: Setup Backend with FastAPI**

```
python backend.py

```

**Phase 3: Setup Frontend with Streamlit**

```
python frontend.py

```

**IMPORTANT**

**Make sure backend python script is running in a separate terminal**
