interduction :-
The following is an example of using Watson to real time transcribe
from Speech to Text  also Text To Speech.

Installation
============
 python3 
to get good started we need to run the following:

   virtualenv -p python3 .venv
   source .venv/bin/activate
   pip install -r requirements.txt

That will build you a clean environment and install the required
pyaudio and websockets libraries for it's use.

we'll need to sign up for the `Watson STT service

In order to connect to the Watson streaming server you need an API Key, and to
specify which region your speech to text service was provisioned in (there are
different gateways per region). You can find these on your IBM Cloud console
for the service you have added.

Once you run transcribe.py with a timeout value (-t) you'll get both
incremental output as data comes back, as well as a final stitching of
things together. The output will look something like this.
