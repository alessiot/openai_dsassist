# Exploring OpenAI ChatGPT API Capabilities as Data Science Assistant

I started this project after watching the videos at https://learn.deeplearning.ai/chatgpt-prompt-eng.
The notebook in this repository summarizes my experiments with the free version of the ChatGPT API. 
The dataset used here is the Concrete Dataset available [here](https://archive.ics.uci.edu/ml/datasets/concrete+compressive+strength) with therein references.

I created a Conda environment that uses the openai library to get connected to the API. These are the commands:

conda create -n openaienv python=3.11 openai

To activate the repository, we can use

conda activate openaienv (to deactivate: conda deactivate)

I also installed additional Python libraries in the environment that I needed along the way.

pip install python-dotenv

pip install fastparquet pyarrow # parquet file support in Pandas

pip install bayesian-optimization

pip install hyperopt

In order to get access to the OpenAI API, we need to sign up to the OpenAI platform and create private API keys as explained [here](https://platform.openai.com/docs/api-reference/authentication).
The API keys can be created after we are logged in by visiting https://platform.openai.com/account/api-keys.
I saved the key in a file named .env as OPENAI_API_KEY="secret key". We have a limit of 3 requests/min






