# Agentic AI Research Assistant — Lab Assignments

This repository contains the Jupyter Notebook submissions for Labs 1–14 for the
**Agentic AI (26ECAC401)** course worklet, **Agentic AI Research Assistant Agent**.
The notebooks follow the lab worklet review sheet and include the concept,
technical stack, implementation, runnable demonstration, evidence instructions,
and reviewer marks section.

## Team

- **Team:** 9
- **Members:** Kartik, Anirudh, Goutam, and Harshad
- **Review date:** 27 October 2026

## Assignments

Open the notebooks in the [`Assignments`](Assignments/) folder:

| Notebook | Lab topic |
|---|---|
| [lab 1.ipynb](Assignments/lab%201.ipynb) | Agent vs Chatbot |
| [lab 2.ipynb](Assignments/lab%202.ipynb) | Tool-Using Agent |
| [lab 3.ipynb](Assignments/lab%203.ipynb) | Skill Creation |
| [lab 4.ipynb](Assignments/lab%204.ipynb) | Memory and Retrieval |
| [lab 5.ipynb](Assignments/lab%205.ipynb) | MCP-Style Connector |
| [lab 6.ipynb](Assignments/lab%206.ipynb) | OpenClaw Runtime |
| [lab 7.ipynb](Assignments/lab%207.ipynb) | Agentic Node Graph |
| [lab 8.ipynb](Assignments/lab%208.ipynb) | Parallel Swarm |
| [lab 9.ipynb](Assignments/lab%209.ipynb) | Deep Research Agent |
| [lab 10.ipynb](Assignments/lab%2010.ipynb) | Cloud Operations Agent |
| [lab 11.ipynb](Assignments/lab%2011.ipynb) | Agentic SDLC Factory |
| [lab 12.ipynb](Assignments/lab%2012.ipynb) | Safety and Governance |
| [lab 13.ipynb](Assignments/lab%2013.ipynb) | Discipline-Specific Agent |
| [lab 14.ipynb](Assignments/lab%2014.ipynb) | Capstone Project Studio |

## Running the notebooks

The notebooks use the implementation in
[`Course Project/Agentic_ai`](Course%20Project/Agentic_ai/). Open this repository
in VS Code or Jupyter, select a Python 3 kernel, and run the notebook cells in
order. The setup cell in each notebook adds the project source directory to
Python's import path. If you cloned the repository to a different location,
update that path in the setup cell to match your local copy.

To install the project's Python dependencies from the repository root:

```powershell
python -m pip install -r "Course Project\Agentic_ai\requirements.txt"
```

To run the project's lab regression suite:

```powershell
Set-Location "Course Project\Agentic_ai"
python run_labs.py
```

The suite exercises the implemented lab workflows. Some demonstrations use
mock/local research data; live academic searches depend on network access and
the configured source APIs.

## Safety note

The research assistant supports human review. Drafting, citations, and research
plans should be verified, and publication or submission should only proceed
after the required faculty approval.
