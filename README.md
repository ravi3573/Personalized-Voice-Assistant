# ChatGPT + Whisper = Voice assistant!

## Project description

This is an small app based on ChatGPT and deployed with Streamlit. The repo also include a version to run directly from console.

* Receives input audio through the microphone
* Transcribe (or translate if necessary) with Wishper API
* Send it to OPENAI ChatGPT API
* Use Google Text-to-Speech API to read ChatGPT response out loud

## How to run it

* Start by cloning the repository:
  `git clone https://github.com/AbuKashan/voice_assistant_with_streamlit.git`
* Create virtual environement using `virtualenv voice_assistant_env`
* Activate virtual environment `voice_assistant_env\Scripts\activate  `
* Install requirements by running ` pip install -r requirements.txt`
* With all libraries installed, we need to manually introduce our own OpenAI api key. You need to create a new file called `myapikeys.py` with this line inside:
  `OPENAI_KEY = "my-apikey-goes-here"`
* With all the set up ready, simply run the bot typing `python chatbot.py`
* You also can run it on the browser making use of the `streamlit` library. Run `streamlit run chatbot_streamlit.py`

## Use instructions:

* Press Enter to start and stop recording.
* Don't forget to reflect on the times we are living on. What a time to be alive!

![](https://github.com/PabloCanovas/chatgpt-whisper-streamlit-voice-assistant/blob/master/img/streamlit_app.png)
