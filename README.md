# GeneriCorp Dataset
This repository represents a corpus of documents all in support of a fictional company called **GeneriCorp**. In the `genericorp/` directory, you will find subdirectories that contain many markdown files all in support of different attributes of this fake company, GeneriCorp. These range from topics like the aforementioned company history as well as how GeneriCorp uses some internally built tools to support their own operations.

## How This Dataset Was Created
Using Generative AI, I began with the initial prompt below to generate the company's history, and everything else has stemmed from there since with minimal prompting from myself:

*Help me to create a fictional history for a fictional company called GeneriCorp. The guidelines on what you can do here are pretty loose. Make the company at least 50 years old, perhaps following the cliche of being started out of a garage. Introduce at least 3 specific individuals who helped build the company up to be as big as it is today. Have at least one interesting little tidbit or story that somebody might laugh at as they hear it, but please make it believable.*

I note this as I intended to avoid as much bias as possible. Beyond this first prompt, all other prompts are more generically positioned to produce generic documents however the Generative AI model saw fit.

Speaking of the Generative AI model, I am using a combination of my personal ChatGPT Plus account with GPT-4o, but at times for convenience's sake, I choose to use the OpenAI API invoking GPT-4o-mini. I unfortunately can't be as transparent with my prompts per the work I'm doing directly in ChatGPT; however, you're more than welcome to view how I programmatically generated sets of documents using the OpenAI API within respective Jupyter notebooks in the `notebooks/` directory.

## Why This Dataset?
In order to be able to sufficiently test out the capabilities of something like a fine tuned LLM or a RAG system, you need a set of data that the model has not been trained against. Unfortunately, this data can be very, very difficult to come across online given that the major LLM providers have largely scraped for that content already and have used it as part of their training data.

As such, I thought it would be useful both for myself and others to simulate a fake dataset that can be specifically used for these kinds of purposes. Of course, it is possible that this content may one day be scraped from the major LLM providers and used as training data, but let's hope that the weights of the model aren't too effectively updated by this content. 😁