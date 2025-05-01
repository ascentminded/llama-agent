# llama-agent

Building an AI agent from pure python and ollama, with a small tutorial on how to learn to use the api.

### Setting up ollama
- Install Ollama from [this page](https://ollama.com/download)
   - Download it and follow the instructions to set it up
- Open bash/powershell (not python) and run ```ollama run llama3.2``` (or other version)
   - Note: ```ollama run llama3:8b``` also works for less powerful computers
   - Now on, ollama will run the llm on the background (not a ram or other issue, I believe)
- Then, ```!pip install ollama``` and ```import ollama``` should allow you to run llama3.2 in python or jupyter.
- Check the tutorial (agent-llama-tutorial.ipynb) for syntax, basic functions, etc.

### The tutorial (agent-llama-tutorial.ipynb)
The jupyter notebook is a walkthrough of important concepts of AI agent development in pure python, using Ollama and llama3.2.
The foundation of this tutorial is [this youtube video](https://www.youtube.com/watch?v=bZzyPscbtI8) by Dave Ebbelaar and [this Anthropic article](http://anthropic.com/research/building-effective-agents)
I've mostly worked through these tutorials myself, and converted them to LLama instead of the GPT api.
It should be fairly readable, but if not, do check out the above video --it's very clearly explained (though the code will differ, obviously), and the anthropic article is famous for a reason.

Cheers,
NB
