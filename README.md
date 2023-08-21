# Podcast to Newsletter using Open AI
A TL;DR for podcast, that turns your favorite podcast into a well-structured newsletter with a concise summary, key highlights, and different chapters.

![podcast_tldr](https://github.com/nikhil1610/podcast-summarizer-OpenAI/assets/54029364/a02b9c41-8cc4-4802-8610-79a654c594ad)

The front end is deployed using [Streamlit](https://streamlit.io/).
And the backend is deployed using [Modal](https://modal.com/).

It uses Open AI's GPT3.5 turbo-16k model to get the summary, key insights, and other information from the podcast transcript. 
The podcast audio is converted into a transcript using [Whisper](https://github.com/openai/whisper).
