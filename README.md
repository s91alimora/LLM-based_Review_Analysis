# LLM-based_Review_Analysis

In this repository, I share a project I did on DataCamp website: (Analyzing Car Reviews with LLMs)[https://app.datacamp.com/learn/projects/2046]

This project requires the use of LLMs to solve diverse language tasks for a car dealership company.

### Project Description:
Car-ing is sharing, an auto dealership company for car sales and rental, is taking their services to the next level thanks to Large Language Models (LLMs).

As their newly recruited AI and NLP developer, you've been asked to prototype a chatbot app with multiple functionalities that not only assist customers but also provide support to human agents in the company.

The solution should receive textual prompts and use a variety of pre-trained Hugging Face LLMs to respond to a series of tasks, e.g. classifying the sentiment in a car’s text review, answering a customer question, summarizing or translating text, etc.

### Project Instructions:
* Use a pre-trained LLM to classify the sentiment of the five car reviews in the `car_reviews.csv` dataset, and evaluate the classification performance.
* The company is recently attracting customers from Spain. Extract and pass the first two sentences of the first review in the dataset to an English-to-Spanish translation LLM. Evaluate the translation quality using the content in `reference_translations.txt` as references.
* The 2nd review in the dataset emphasizes brand aspects. Load an extractive QA LLM to formulate the question `"What did he like about the brand?"` and obtain an answer.
* Summarize the last review in the dataset, into approximately 50-55 tokens long.
