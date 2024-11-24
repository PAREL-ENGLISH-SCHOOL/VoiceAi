# LiveKit Assistant

First, create a virtual environment, update pip, and install the required packages:

```
$ python -m venv venv
$ venv/scripts/Activate.ps1
$ pip install -U pip
$ pip install -r requirements.txt
```

You need to set up the following environment variables:

```
LIVEKIT_URL=...
LIVEKIT_API_KEY=...
LIVEKIT_API_SECRET=...
DEEPGRAM_API_KEY=...
CARTESIA_API_KEY=...
```

Then, run the assistant:

```
$ python assistant.py download-files
$ python assistant.py start
```

Finally, you can load the [hosted playground](https://agents-playground.livekit.io/) and connect it.
