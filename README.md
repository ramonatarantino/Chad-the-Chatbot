# Chad the Chatbot

## Overview
**"Chad the Chatbot"** is an advanced AI chatbot designed to provide expert answers in the domain of statistics. This project showcases the development process of Chad, from dataset creation to the final chatbot implementation.

## Project Components
- Custom Dataset Creation: The dataset for training Chad was uniquely curated through web scraping from the Cross Validated - Stack Exchange website, focusing on statistics-related content.

- Model Fine-tuning: Chad is powered by the "EleutherAI/gpt-neox-20b" model, which was fine-tuned specifically for this application. The fine-tuning process incorporated advanced techniques like bitsandbytes, 4-bit quantization, and QLoRA to enhance performance and efficiency.

- Zero-shot Classification: To ensure Chad's responses are relevant, the "facebook/bart-large-mnli" model is used for zero-shot classification. This step filters out questions not related to statistics, maintaining the chatbot's focus and accuracy.

- Chatbot Implementation: The culmination of this project is the creation of Chad, a chatbot that seamlessly integrates question classification with answer generation. Users can ask statistics-related questions, and Chad will provide informed, accurate responses.

## How It Works
Users interact with Chad by posing questions related to statistics.

Each question is processed using zero-shot classification to determine its relevance to the domain.

Relevant questions are passed to the fine-tuned GPT-NeoX-20b model, which generates the responses.

Chad delivers the generated answer, offering users insights and information on their queried topics.
