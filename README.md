# ChatGPT Prompt Engineering
This repository is a part of ChatGPT Prompt Engineering course from [deeplearning.ai](https://deeplearning.ai). You can access the course [here](https://learn.deeplearning.ai/chatgpt-prompt-eng/lesson/1/introduction?_gl=1*12zf2uv*_ga*NDU3MTIxMzQwLjE2ODI2NjM0MTM.*_ga_PZF1GBS1R1*MTY5NjIzODM2MC4xNS4wLjE2OTYyMzgzNjEuNTkuMC4w).<br>
The repository contains the jupyter notebook files from the course.<br>
You can go through the notebooks to:<br>
- Learn prompt engineering best practices for application development
- Discover new ways to use LLMs, including how to build your own chatbot
- Gain hands-on practice writing and iterating on prompts using the OpenAI API<br>
<br>
In all of these notebooks, I have used the following method/format to setup my OpenAI API key:<br><br>

```python
import openai
import os

from dotenv import load_dotenv, find_dotenv
_ = load_dotenv(find_dotenv()) # read local .env file

openai.api_key  = os.getenv('OPENAI_API_KEY')
```
<br>
This is a recommended method as in this way there is no chance of exposing your OpenAI API key to the world.<br><br>
An alternate way is to directly configure the key as:<br>

```python
import openai
openai.api_key = "sk-..."
```
