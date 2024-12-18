# Voice Ai : the ultimate realtime Ai bot

## Description
It is a real time chatbot that combines voice, text and vision capabilities to deliver a seamless and interactive user experiences. Designed for versatility, It understands spoken language, processes text with precision, for dynamic applications like virtual assistance, education and many more.


## Disclaimer
This is made for a science exhibition project. There is a lot of room for improvement. It is just made for prototype purpose

## AI model
This uses LLAMA 3.2 LLM preview model. It can make mistakes. If the information given by AI is critical for you, you should cross check the results.

## Table of Content
- [Prerequisites](#prerequistes)
- [Getting Keys](#getting-required-keys-completely-free-and-secure)
- [Setting Up Project](#setting-up-project)
- [Environment Variables](#environment-variables)
- [Running](#running)

## Prerequisites
- Download the Latest Version of Python from [python.org](https://www.python.org/downloads/)
- If you are going to edit the code then also download a python code editor for better experience. [VScode](https://code.visualstudio.com/Download) with Python extension is recommended.
- Some basic knowledge of terminal of your system. If not, you can just follow our given commands(for windows). For other system you can ask me or google it.

## Getting required keys (Completely free and secure)
1) Create a Groq account and get a api key
2) Create a Livekit account
3) Create a Livekit project (this will give you LIVEKIT_URL)
4) Generate API Key (this will also give you api secret)
5) Create a Deepgram account
6) Get a api key
7) Create a Cartesia account and get a api key

## Setting Up Project
Clone or Download this repo
Create a virtual environment, update pip, and install the required packages using following commands (this is for windows):
```
$ python -m venv venv
$ venv/scripts/Activate.ps1
$ pip install -U pip
$ pip install -r requirements.txt
```
## Environment Variables

You need to set up the following environment variables in .env.local file (steps to get this is giving in [Getting Keys](#getting-required-keys-completely-free-and-secure)):
```
LIVEKIT_URL=
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
DEEPGRAM_API_KEY=
GROQ_API_KEY=
CARTESIA_API_KEY=
```

## Running
Then, run the assistant web socket:

```
$ python assistant.py download-files
$ python assistant.py start
```

Connect to the assistant web socket with the livekit project name show on screen [hosted playground](https://agents-playground.livekit.io/) of livekit.
