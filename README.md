# NER and POS Tagging with DISTILBERT

<img src="https://github.com/user-attachments/assets/11837915-fb6a-4a4b-8909-9aff07b3b4c5" alt="image" width="400" height="300">


This project showcases a fine-tuned DISTILBERT model that performs Named Entity Recognition (NER) and Part-of-Speech (POS) tagging. The model can identify various parts of speech in a sentence and recognize named entities, providing a deeper understanding of the sentence structure.

## Overview

The model is trained to accurately identify parts of speech and named entities within a given text. This project leverages Hugging Face’s `transformers` library and is deployed using Gradio for an interactive and user-friendly experience.

## Demo

You can interact with the live demo [here](https://huggingface.co/spaces/Tarun-1999M/NER_POS_tagging).

## How It Works

The interface is built using Gradio, allowing users to input text and receive predictions for both parts of speech and named entities. The model returns results in a JSON format, displaying the tags and their corresponding words.

## Features

- **Named Entity Recognition**: Identifies entities such as names, locations, organizations, etc.
- **Part-of-Speech Tagging**: Tags words with their grammatical roles (e.g., noun, verb, adjective).
- **Interactive Interface**: Powered by Gradio for an easy-to-use experience.
- **Predefined Examples**: Includes sample texts to get you started.

## Abbreviations Explained

- **ADJP**: Adjective Phrase
- **ADVP**: Adverb Phrase
- **CONJP**: Conjunction Phrase
- **INTJ**: Interjection
- **LST**: List Item Marker
- **NP**: Noun Phrase
- **PP**: Prepositional Phrase
- **PRT**: Particle
- **SBAR**: Subordinating Conjunction Clause
- **UCP**: Unlike Coordinated Phrase
- **VP**: Verb Phrase
- **O**: Outside of a named entity

## Example Prompts

- *Albert Einstein was a physicist and he developed the theory of relativity.*
- *Python is a programming language that I use daily.*

## How to Use

1. Enter your text in the textbox.
2. Click the submit button to receive POS and NER tags.
3. View the results in JSON format, detailing the identified tags.

## Setup

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Tarun-1999M/NER_POS_tagging.git
   cd NER_POS_tagging
