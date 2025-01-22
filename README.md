# Reflection Pattern for GenAI using Snowflake
Reflection Pattern for LLM This notebook demostrates the Reflection pattern for LLMs as defined by Andrew Ng of DeepLearning.ai. The goal is to show how to prompt an LLM, have another prompt "reflect" on the answer, and incorporate the revisions from the reflection.  This examples demonstrates how to generate python code for a Merge Sort.

# Approach
This notebook uses
* llama for the LLM
* streamlit (st) library to display formatted markdown.
* Static system prompt (well, it is just a pattern!)


## TODO:
* Make it easy to change LLMs, Default to using anthropic sonnet 3.5.
* Create a python library to call from stand alone python 
* Expand the pattern to all user to define the system prompt
* Expant to use RAG for answers as well.
* Improve performance...
