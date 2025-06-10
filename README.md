

## Introduction


Using Large-Language Models (LLMs) to design a spacecraft that is a low-cost Bracewell probe.

## Installation

```R
pip install -r requirements.txt


mkdir -p /home/codespace/.local/lib/python3.12/site-packages/google/colab

```

Add a new file called `.env` and type in the following:

```R
OPENAI_API_KEY = "<yourapikeywhichisprivate>"
```

Create a `.gitignore` file and add the following

.env

You can then execute the following notebooks in Github codespaces or Google Colab.


## Files

`RAG_sciencefiction_superintelligence_SB.ipynb`: Notebook with RAG for reenvisioning superintelligence with science fiction

`papers` folder has documents for RAG

`.jinja` files have system prompts for querying the LLM

`.txt` files have logs for the output of LLMs


`simple_agent_ag2.ipynb`: Simple agent to call OpenAI and ask it to re-envision AI repeatedly

`deep_research_agent_ag2.ipynb`: DeepResearch agent to re-envision AI

`deep_research_agent_ag2_spacecraftdesign.ipynb`: DeepResearch agent 


https://github.com/neelsoumya/spacecraft_design_LLM/blob/main/deep_research_agent_ag2_spacecraftdesign.ipynb

## Acknowledgements

Accelerate Programme for Scientific Discovery

## Contact

Soumya Banerjee

sb2333@cam.ac.uk
